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
### UPDATED 2021
##OBS Audio Filters

Follow this inOrder
###Noise Suppresion
```Method "RNNoise (higher quality)"```
###Expander
```Presets "Expander"```
```Ratio "2.00:1"```
```Threshold "-40.00dB"```
```Attack "3ms"```
```Release "35"```
```Output Gain "7.50dB"```
```Detection "RMS"```
###Compressor
```Ratio "8.00:1"```
```Threshold "-18.00dB"```
```Attack "3ms"```
```Release "35"```
```Output Gain "1.30dB"```
```Sidechain/Ducking Source "None"```
###Limiter
```Threshold "-11.00dB"```
```Release "30"```


### Addon for OBS
[NDI OBS Plugin](https://github.com/Palakis/obs-ndi/releases/tag/4.9.1)

[NDI Virtual INPUT ver4.90](https://b0e4fe3766b8739d74f9-437b8dd50f60b69cf0974b538e50585b.ssl.cf1.rackcdn.com/Utilities/NDI_Tools/NDI%204%20Tools.exe)

MACOS

[NDI Tools for Mac link. ](https://b0e4fe3766b8739d74f9-437b8dd50f60b69cf0974b538e50585b.ssl.cf1.rackcdn.com/Utilities/SDK/NDI_SDK_Mac/NewTekNDIToolsForMacOS.dmg)

[NDI|HX Driver for Mac link](https://077331edbcb8e68d212a-bfe57ec74076e9cb0c74346d8bd35c21.ssl.cf1.rackcdn.com/NDIHX/OSX/NewTekNDIHXDriverForMacOS.dmg)
