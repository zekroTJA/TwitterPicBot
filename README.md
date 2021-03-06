# TwitterPicBot

So you have some questions or want to join my developer community discord? Take a look! :^)
<br/><a href="http://discord.zekro.de"><img src="https://discordapp.com/assets/fc0b01fe10a0b8c602fb0106d8189d9b.png" width="100"/></a>

## Function

This is a little bot posting periodically pictures from a list of Deviantart/Artstation atrwork links to your twitter account.

Supported Platforms:  *`Note: The bot is not supporting pixiv colletion and R18 links yet!`*<br/>
<img src="http://orig03.deviantart.net/0c20/f/2015/052/3/4/deviantart_logo_2__green_original___by_siamvocaloid01-d8ix39x.png" width="45"><img src="http://t07.deviantart.net/l3Ekd32TZNo9y1M7I8qlqNTm9jY=/fit-in/300x900/filters:no_upscale():origin()/pre03/c38a/th/pre/f/2015/322/4/e/artstation_logo_vertical_white_800_by_phaeton99-d9h4s5p.png" width="50"><img src="http://farrowandball.btxmedia.com/pws/client/images/catalogue/products/102005/zoom/102005.jpg" width="15"><img src="http://orig00.deviantart.net/72da/f/2015/183/9/f/pixiv_logo_icon_png_by_vampirehelenaharper-d8zog8c.png" width="45">
<br/><br/>

<img src="http://image.prntscr.com/image/7394b1559737428db2dbe196c9e08f2d.png"/>

## Installation

<img src="https://image.flaticon.com/icons/svg/188/188234.svg" width="15"/>  Download 'TwitterPicBot.jar', 'tokens.txt' and 'piclist.txt' and put these files together in a folder.
<br/><br/><img src="http://image.prntscr.com/image/66fd1df88dda4d3594fa49120c9e8358.png" width=""/>

<img src="https://image.flaticon.com/icons/svg/188/188235.svg" width="15"/>  Open the <a href="https://apps.twitter.com/" target="_blank">Twitter Application Management</a> and create a App to connect the bot with your Twitter account.

<img src="https://image.flaticon.com/icons/svg/188/188236.svg" width="15"/>  Now get your consumer and acces credentials and enter them in the file 'tokens.txt'.
<br/><br/><img src="http://image.prntscr.com/image/18d93acf2730406c81c891abf25e1ea9.png" width=""/>

<img src="https://image.flaticon.com/icons/svg/188/188237.svg" width="15"/>  Finally, start the bot in console with the following command:
```bash
java -jar TwitterPicBot.jar -start 16:00:00_06-12-2017 -interval 4
```
*`In this example, the bot will post a picture every 4 hours after 16:00 in 06th of December 2017`*

If you want to run it on a linux server, use this command:
```bash
screen -L -S picBot java -jar TwitterPicBot.jar -start 16:00:00_06-12-2017 -interval 4
```

<img src="https://image.flaticon.com/icons/svg/188/188238.svg" width="15"/>  At last, put some nice DeviantArt Artworks or Artstation Artwoks as links in the 'piclist.txt'. The bot will post them and will delete the last send picture link out of the list.
<br/><br/><img src="http://image.prntscr.com/image/1fb0b161e25f45d4a94cc7dd4ab0fd00.png" width=""/>

## Used libraries
- <a href="http://twitter4j.org/en/index.html">twitter4j</a>
- <a href="https://jsoup.org/">jsoup</a>
- <a href="https://github.com/mwanji/toml4j">Toml4j</a>
