
Our model can generate long-form, variable-length stereo music at 44.1kHz like this one:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

And stereo sound effects at 44.1kHz like this one:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>


## Stereo sound effects

This project is built around using markdown content to make a website. 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>



## Long-form stereo music: comparison with state-of-the-art


**Prompt # 1**: This song contains someone strumming a melody on a mandolin while more people are whistling along. Then a mandolin, an e-bass and an acoustic guitar are playing a short melody in a lower key before breaking into the next part along with flutes and percussions. This song may be played outside by musicians performing. 

|**Our model**|**MusicGen-large**|**MusicGen-stereo**|**AudioLDM2**
|(stereo, 44.1kHz)|(mono, 32kHz)|(stereo, 32kHz)|(mono, 48kHz)
| <audio controls preload=False><source src="audio/ZTVMsW1h3bI_stableaudio.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenlarge.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenstereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_audioldm248k_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

**Prompt #2**: The commercial music features a groovy piano melody played over snare rolls in the first half of the loop. Right after, there is a drop that consists of a punchy "4 on the floor" kick pattern, shimmering hi hats, claps, groovy piano and wide synth lead melody. It sounds happy, fun, euphoric and exciting.

|Our model|MusicGen-large|MusicGen-stereo|AudioLDM2| 
|(stereo, 44.1kHz)|(mono, 32kHz)|(stereo, 32kHz)|(mono, 48kHz)|
| <audio controls preload=False><source src="audio/ZK5M3DZejzk_stableaudio.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>| <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenlarge.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>| <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenstereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_audioldm248k_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | 



## Sound effects: : comparison with state-of-the-art

**Prompt # 1**: This song contains someone strumming a melody on a mandolin while more people are whistling along. Then a mandolin, an e-bass and an acoustic guitar are playing a short melody in a lower key before breaking into the next part along with flutes and percussions. This song may be played outside by musicians performing. 

Certainly! Here's a rewritten version:

| Model | MusicGen-large | MusicGen-stereo | AudioLDM2 | 
| ------ | -------------- | --------------- | --------- |
| (stereo, 44.1kHz) | (mono, 32kHz) | (stereo, 32kHz) | (mono, 48kHz) |
| <audio controls preload=False><source src="audio/ZTVMsW1h3bI_stableaudio.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenlarge.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenstereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_audioldm248k_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt #2**: The commercial music features a groovy piano melody played over snare rolls in the first half of the loop. Right after, there is a drop that consists of a punchy "4 on the floor" kick pattern, shimmering hi hats, claps, groovy piano and wide synth lead melody. It sounds happy, fun, euphoric and exciting.

| Model | MusicGen-large | MusicGen-stereo | AudioLDM2 | 
| ------ | -------------- | --------------- | --------- |
| (stereo, 44.1kHz) | (mono, 32kHz) | (stereo, 32kHz) | (mono, 48kHz) |
| <audio controls preload=False><source src="audio/ZK5M3DZejzk_stableaudio.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenlarge.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenstereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_audioldm248k_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | 


## Variable-length music

30 sec music:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

60 sec music:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

Note that the rest of examples in this website (95 sec music, or 10 sec sound effects) are generated with the same variable-length model.


## Autoencoder: reconstruction examples

Explain a little bit wht the user wil listen here..

| Ground-truth | Autoencoder reconstruction |
|-|-|
| <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
