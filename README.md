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
