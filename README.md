
Our model can generate long-form, variable-length stereo music at 44.1kHz like this one:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

And stereo sound effects at 44.1kHz like those ones:

Prompt #1: Motorbike passing by. High-quality. Stereo.

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

Prompt #2: Sports car passing by. High-quality. Stereo.

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>


## Stereo sound effects

Differently from pervious state-of-the-art models, ours can generate stereo sound effects.

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio>

## Variable-length music

30 sec music:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

60 sec music:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

Note that the rest of examples in this website (95 sec music, or 10 sec sound effects) are generated with the same variable-length model that can generate both music and sound effects at 44.1kHz stereo.

## Variable-length sound effects

30 sec:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

60 sec:

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

<audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> 

Note that the rest of examples in this website (95 sec music, or 10 sec sound effects) are generated with the same variable-length model that can generate both music and sound effects at 44.1kHz stereo.

## Long-form stereo music: comparison with state-of-the-art


**Prompt # 1**: This song contains someone strumming a melody on a mandolin while more people are whistling along. Then a mandolin, an e-bass and an acoustic guitar are playing a short melody in a lower key before breaking into the next part along with flutes and percussions. This song may be played outside by musicians performing. 

| Our Model | MusicGen-large | MusicGen-stereo | AudioLDM2 | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 32kHz)* | *(mono, 48kHz)* |
| ------ | -------------- | --------------- | --------- |
| <audio controls preload=False><source src="audio/ZTVMsW1h3bI_stableaudio.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenlarge.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_musicgenstereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZTVMsW1h3bI_audioldm248k_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt #2**: The commercial music features a groovy piano melody played over snare rolls in the first half of the loop. Right after, there is a drop that consists of a punchy "4 on the floor" kick pattern, shimmering hi hats, claps, groovy piano and wide synth lead melody. It sounds happy, fun, euphoric and exciting.

| Our Model | MusicGen-large | MusicGen-stereo | AudioLDM2 | 
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(stereo, 32kHz)* | *(mono, 48kHz)* |
| ------ | -------------- | --------------- | --------- |
| <audio controls preload=False><source src="audio/ZK5M3DZejzk_stableaudio.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenlarge.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_musicgenstereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/ZK5M3DZejzk_audioldm248k_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |


## Sound effects: comparison with state-of-the-art

**Prompt # 1**: Clicking and sputtering then eventual revving of an idling engine.

| Model | Audiogen-medium | AudioLDM2 |
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(mono, 48kHz)* |
| ------ | -------------- | --------------- | 
| <audio controls preload=False><source src="audio/103136_stableaudio_audio.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/103136_audiogen_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/103136_audioldm248k_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

**Prompt #2**: Birds chirping loudly.

| Model | Audiogen-medium | AudioLDM2 |
| *(stereo, 44.1kHz)* | *(mono, 32kHz)* | *(mono, 48kHz)* |
| ------ | -------------- | --------------- | 
| <audio controls preload=False><source src="audio/37008_stableaudio_audio.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/37008_audiogen_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> | <audio controls preload=False><source src="audio/37008_audioldm248k_stereo.wav" type="audio/mpeg">Audio not supported by your browser.</audio> |

## Autoencoder: reconstructions

This experiment is to evaluate the audio fidelity capabilities of the autoencoder. On the left, we have the ground truth recording. On the right, we take the ground truth recording and end pass it through the autoencoder. Note that the autoencoder reconstruction is fairly transparent, very close to the ground truth.

| Ground truth | Autoencoder reconstruction |
|-|-|
| <audio controls preload=False><source src="audio/1197.flac" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/1197_ae.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/1243.flac" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/1243_ae.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/206251.flac" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/206251_ae.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/233076.flac" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/233076_ae.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
| <audio controls preload=False><source src="audio/451.flac" type="audio/mpeg">Your browser does not support the audio element.</audio> | <audio controls preload=False><source src="audio/451_ae.wav" type="audio/mpeg">Your browser does not support the audio element.</audio> |
