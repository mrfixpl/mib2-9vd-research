# mib2-9vd-research
Trying to power subwoofer from stock MIB2 main unit

## MST2 dataset addresses
* `0x000200` - `ASAM_ODX_MUX_dataset` - unit identifier string (contains amplifier channel config info)
* `0x003000` - `audio_parameter_sound_dataset` DSP settings (audio effects, filters, delays, limiters).
* `0x003B00` - `audio_parameter_sound_configuration_dataset` graphic user interface settings (sliders and knobs).
* `0x003600` - `audio_announce_dataset`

# Reference
* https://www.drive2.ru/l/613971966948312999/
* https://www.drive2.ru/l/611261670785849626/
* https://mqb-blog.com/en/2022/02/21/sound-dataset/
* https://github.com/NumberOneBot/mqb-mib2-sound-datasets
