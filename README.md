# my OBS info


### OBS Scene Timer - Lua Advanced Timer 0.4.1

[Website info](https://obsproject.com/forum/threads/advanced-timer.81539/page-2)

[Download](https://obsproject.com/forum/resources/advanced-timer.637/download)


## Filters for MIC

### Audio Filters Basic configuration
```
        Noise Suppression
		Suppression Lelel -33dB
	Noise Gate  = dont need if you use Expander
		Close Threshold -32db
		Open Threshold -32dB
			Attack Time 5ms
			Hold Time 200ms
			Release Time 150ms
	Expander
		Presents Expander
			Ratio  3:00:1
			Threshold -40.10 dB
			Attack  6ms
			Release 345 ms
			Output Game
	Compressor
		Ratio  10:00:1
		Threshold  -21.60 dB
		Attack   6ms
		Release  60ms
		Output Gain  3.80 dB
	Limiter
		Threshold -6.00 dB
		Release 60 ms
```
###### UPDATED 2021
## OBS Audio Filters

##Follow this inOrder
```
Plantronics Blackwire 3225 Series USB
```
##### Gain
``` 
	Gain 6.60dB
```

##### Noise Suppresion
``` 
	Method "RNNoise (higher quality)" 
```
##### Expander
```
	Presets "Expander"
	Ratio "2.00:1"
	Threshold "-40.00dB"
	Attack "5ms"
	Release "30"
	Output Gain "6.50dB"
	Detection "RMS" 
```
##### Compressor
```
	Ratio "8.00:1"
	Threshold "-18.00dB"
	Attack "3ms"
	Release "35"
	Output Gain "2.70dB"
	Sidechain/Ducking Source "None"
```
##### Limiter
````
	Threshold "-7.50dB"
	Release "30"
````

```
VLC set volume 80%
```

### OBS Studio Plugins
[NDI OBS Plugin](https://github.com/Palakis/obs-ndi/releases/tag/4.9.1)

added 2021
[NDI Virtual INPUT ver4.9x](https://downloads.ndi.tv/Tools/NDI%204%20Tools.exe)

old link
[NDI Virtual INPUT ver4.90](https://b0e4fe3766b8739d74f9-437b8dd50f60b69cf0974b538e50585b.ssl.cf1.rackcdn.com/Utilities/NDI_Tools/NDI%204%20Tools.exe)

[NDI® Analysis Tool (Beta)](https://downloads.ndi.tv/Tools/NDI%204%20Analysis%20BETA.exe)

[NDI Newtek connect](https://go.newtek.com/e/428312/NDICONNECT/6lvf6m/1035736921?h=KeoId4cwIseDqRTiZy0j5MLvTsD6i-Kc0LK_aEMa1gU)

MACOS

[NDI Tools for Mac link. ](https://b0e4fe3766b8739d74f9-437b8dd50f60b69cf0974b538e50585b.ssl.cf1.rackcdn.com/Utilities/SDK/NDI_SDK_Mac/NewTekNDIToolsForMacOS.dmg)

[NDI|HX Driver for Mac link](https://077331edbcb8e68d212a-bfe57ec74076e9cb0c74346d8bd35c21.ssl.cf1.rackcdn.com/NDIHX/OSX/NewTekNDIHXDriverForMacOS.dmg)

[Audio Monitor 0.4.1](https://obsproject.com/forum/resources/audio-monitor.1186/)

[StreamFX 0.8.3](https://github.com/Xaymar/obs-StreamFX/releases/download/0.8.3/streamfx-windows2019-0.8.3.0-ee225959.exe)
``` 
https://github.com/Xaymar/obs-StreamFX/releases/tag/0.8.3
```

```
ffmpeg -f dshow -i video="HP HD Webcam":audio="Headset Microphone (Plantronics Blackwire 3225 Series)" -profile:v high -pix_fmt yuvj420p -level:v 4.1 -preset ultrafast -tune zerolatency -vcodec libx264 -r 10 -b:v 512k -s 640x360 -acodec aac -ac 2 -ab 32k -ar 44100 -f mpegts -flush_packets 0 udp://192.177.7.70:5000?pkt_size=131


ffmpeg -f dshow -i video="Logitech Webcam C930e":audio="Headset Microphone (Plantronics Blackwire 3225 Series)" -profile:v high -pix_fmt yuvj420p -level:v 4.1 -preset ultrafast -tune zerolatency -vcodec libx264 -r 10 -b:v 512k -s 640x360 -acodec aac -ac 2 -ab 32k -ar 44100 -f mpegts -flush_packets 0 udp://192.177.6.85:5000?pkt_size=1316

ffplay UDP://@127.0.0.1:5000
```

