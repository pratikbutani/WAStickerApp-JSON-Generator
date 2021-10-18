# WAStickerApp-JSON-Generator
A JSON Generator for WhatsApp Sticker Pack Apps. Check it now : http://pratikbutani.com/wastickerapp/ 

![WAStickerApp-JSON-Generator](https://raw.githubusercontent.com/pratikbutani/WAStickerApp-JSON-Generator/master/JSON_Creator_WhatsAppSticker_Pack.png)

We are creating many apps for WhatsApp Stickers after they have announced sticker features in Android and iOS App.

I have also created some apps for [WhatsApp Stickers](https://play.google.com/store/apps/developer?id=WAStickers+Collection+Apps) but got some difficulties to create JSON for `content.json` file. Every developer faced this problem, Believe Me.

Here is the solution, I have created tool [Convert Image names to JSON Array (WAStickerApp)](http://pratikbutani.com/wastickerapp/) which can help you to get JSON by giving details of Sticker Pack.

You can upload following details:
- Folder Name (Identifier)
- Sticker Pack Name
- Publisher
- Tray Image (with .png)
- Publisher Email
- Publisher Website
- Privacy Policy URL
- Licence Agreement Website
- Images (Only .webp)

It will give full array in JSON as below:

**Format:**
```
{
    "android_play_store_link": "",
    "ios_app_store_link": "",
    "sticker_packs": [
        {
            "identifier": "1",
            "name": "My Sticker Pack",
            "publisher": "Pratik Butani",
            "tray_image_file": "placeholder.png",
            "image_data_version","1",
            "avoid_cache":false
            "publisher_email": "pratik13butani@gmail.com",
            "publisher_website": "pratikbutani.com",
            "privacy_policy_website": "your-url.com/privacy_policy.php",
            "license_agreement_website": "your-url.com/license.php",
            "stickers": [
                {
                    "image_file": "banner.webp",
                    "emoji": [
                        "",
                        ""
                    ]
                },
                {
                    "image_file": "bg_img.webp",
                    "emoji": [
                        "",
                        ""
                    ]
                },
                {
                    "image_file": "ic_chef.webp",
                    "emoji": [
                        "",
                        ""
                    ]
                }
            ]
        }
    ]
}
```

You can read full article here : [JSON Creator for WhatsApp Sticker Pack](https://medium.com/mindorks/json-creator-for-whatsapp-sticker-pack-1ffb2719f562)

I hope you will love it.

**No one has ever become poor by giving. <3 <3**

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=46Q5USNZNGKML)

Thank you.
