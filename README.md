![greetings](/Asset/Leonis.png)
<!-- BADGES -->
<h1>
  <a href="#--------">
    <img alt="" align="right" src="https://badges.pufler.dev/visits/closebox73/Leonis?style=for-the-badge&color=282C35&logoColor=9F2B2B&labelColor=282C35"/>
  </a>
</h1>
A Conky themes pack which I made in hopes of beautifying your desktop 

## Showcase :

#### [Regulus](/Regulus) theme

![](/Regulus/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/GAg4h8_mPCs)

#### [Rasalas](/Rasalas) theme

![](/Rasalas/preview.png)

#### [Alterf](/Alterf) theme

![](/Alterf/preview.png)

#### [Adhafera](/Adhafera) theme

![](/Adhafera/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/EQ2srpKQkAU)
#### [Zozma](/Zozma) theme

![](/Zozma/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/eriuKJwcdjI)
----------------------------------------------------------------
### Featured
#### [Saiph](/Saiph) theme

![](/Saiph/preview.png)
#### [Izar](/Izar) theme

![](/Izar/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/TsNjhAkCbY)

#### [Kochab](/Kochab) theme

![](/Kochab/preview.png)

#### [Syrma](/Syrma) theme

![](/Syrma/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/cRCyuPRuVfw)
----------------------------------------------------------------

## Note :
- syntax configuration of this theme for conky version 1.10.8 or newer
- the default folder for this theme is in ~/.config/conky if it doesn't exist please create one
- The music player I used was `mpd`
- If the network speed doesn't work, try changing the network interface according to yours, the way to check is as follows
	![](/Asset/Wlan.png)
- I currently use Openbox, sometimes for other DE requires a slightly different setting
	if you know how to set it on another DE (if an error occurs) please let me know and I will post it here 
- All fonts i get from:
	 - [Dafont](https://www.dafont.com)
	 - [Google Fonts](https://fonts.google.com) 

## Requirements :
- Conky version 1.10.8 or newer ( open this  [Link](https://github.com/brndnmtthws/conky) for instalation )
- for the weather theme I download the data using `curl` in json format, and use `jq` to process the data, please install first.
- if you want to use the GUI when installing the theme, please install [conky-manager2](https://github.com/zcot/conky-manager2)

## How to use theme :
- Clone this repo by command
  ```bash
  git clone https://github.com/closebox73/Leonis.git
  ```
- Move one or more theme folders into ~/.config/conky/
- Open a folder that will be used and Install all font in fonts folder ( if you haven't installed the font ) then update font cache
- For weather theme you must have API KEY and city id ( you can get it [Here](https://openweathermap.org) and fill weather.sh in scripts folder
- Execute `start.sh`
- If you use conky-manager2, just check the theme to be installed
	![](/Asset/CM2.png)
- Done

## Last
- these themes are inspired by
	- KWGT widget for Android
	- ZOOPER widget
	- RAINMETER 
