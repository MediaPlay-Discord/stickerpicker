# Maunium sticker picker
A fast and simple Matrix sticker picker widget. Tested on Element Web, Android & iOS.

---

# Adding the MPD sticker pack
Using the `/devtools` command on Element Web, edit the `m.widgets` account data event, then replace the content with:
```
{
    "stickerpicker": {
        "content": {
            "type": "m.stickerpicker",
            "url": "https://mediaplay-discord.github.io/stickerpicker/web?theme=$theme",
            "name": "Stickerpicker",
            "data": {}
        },
        "sender": "@you:matrix.server.name",
        "state_key": "stickerpicker",
        "type": "m.widget",
        "id": "stickerpicker"
    }
}
```

You can also get the MPD sticker pack folder (web/packs/MPD-Sticker-Pack.json and index.json) if you'd like to create a sticker pack on your own stickerpicker.

---

## Preview
### Element Web
![Element Web](preview-element-web.png)

### Element Android
![Element Android](preview-element-android.png)

### Element iOS (dark theme)
![Element iOS](preview-element-ios.png)
