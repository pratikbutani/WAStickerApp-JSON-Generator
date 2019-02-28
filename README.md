# WAStickerApp-JSON-Generator

I have created script that will give you JSON of selected files.

[Convert Image names to JSON Array (WAStickerApp)](http://pratikbutani.com/wastickerapp/)

That will allows you to:
- Folder Name (Identifier)
- Sticker Pack Name
- Publisher
- Tray Image (with .png)
- Publisher Email
- Publisher Website
- Privacy Policy URL
- Licence Agreement Website
- Images (Only .webp)

It will give full pack array in JSON.

**Format:**
```
{
    "android_play_store_link": "",
    "ios_app_store_link": "",
    "sticker_pack": [
        {
            "identifier": "1",
            "name": "My Sticker Pack",
            "publisher": "Pratik Butani",
            "tray_image_file": "placeholder.png",
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

Hope it will helps.

**No one has ever become poor by giving. <3 <3**

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=46Q5USNZNGKML)

Thank you.
