# gccsoundboard 🎛
Instructions and recommendations for operation of the GCC soundboard.

# Recommended Fader Levels 🏆

Main fader at -10.0

Reasons why:
1. Other faders can be run at or near 0.0 which makes for best control for mixing.
2. Momentary loudness won't be overpowering
3. Mixing mistakes will be harder to hear at lower levels. Mixing mistakes are easier to hear at 0 or +3.

Monitors at -5.0

Reasons why:
1. Loud enough that singers can hear themselves
2. Avoids feedback loops with the SM58 stage mics

Narthex at -5.0. This might need adjusted in the future.

ALS bus at 0.0

Reasons why:
1. The volume of the assisted listing system can be adjusted to taste by each individual.
2. The bus is only for pulpit speaker and pastor mic pack. You can add stage mics on the fly by pressing **Fader Flip**.

### Pastor Mic 🎙
Pastor fader should be run at 0.0. Adjust as needed for announcements, communion, etc. Run it as quiet as possible without making it hard to hear what is being said.

Pastor microphone is a Shure QLXD1 bodypack. It is an over-the-ear microphone. The preamp gain can be lower than the gain we use for the SM58 stage mics because the pastor microphone is close to the person's mouth. This results in an excellent signal-to-noise ratio. I typically run the preamp gain so that the pastor is peaking at the top of the green zone (-18 dBu). Use the dynamic compressor to reduce the maximum amplitude by 6 dB during energitic moments of the sermon. On the dynammic compressor is a setting labeled **Gain** or **Makeup gain**. Set it to a positive number so that you can comfortably keep the fader at 0.0. The quiet moments are still audible in the PA speakers.

The bodypack might have a gain adjustment on the pack. We never change it. 

### Vocalist Mics
Cardiod mics are used for vocalist mics. These reject rear noise, which is good because we are using stage monitors.

# Loudness meter 📢
Recommended loudness for our style goal is to have **peaks at 85** and constant loudness around 78 to 83 dBA. Also consider there are lots of little ears in the room so stay well below 88 dBA. 

Imagine hearing anything on stage naturally with the gentle aid of amplification. Try to keep the amount of boost from the PA speakers at or slightly above the original source. Worded another way, there can be a big gap between a PA speaker output and the original sound source; our style goal is to get that gap to be as small as possible.

Sermon should _peak_ at 82 dBA or less so that congregational ears are not fatigued.

## Example Service
These were maximum momentary peaks measured during a real service that sounded good.
| Part of the service                   | Decibels (dBA) |
|---------------------------------------|----------------------------|
| Song 1                                | 83                         |
| Song 2                                | 85                         |
| Song 3                                | 84                         |
| Sermon                                | 78                         |
| Song during distribution of the bread | 82                         |
| Song during distribution of the wine  | 81                         |
| God's blessing                        | 79                         |

_These measurements are all A-weighted (dBA), which means the frequency curve of the device are adjusted to the human ear's response, which means the low end rumble will not affect the measurement. We want to measure loudness of things that are around 500 to 4000 hz (human voices) and don't really care how loud the low rumbles at 200 hz and below. If we did then we would measure C-weighted loudness instead of A-weighted loudness._

# Other Notes
### Shutdown order
Turn the key to shutdown the amps BEFORE turning off the mixing console. This will prevent audio pops being sent to the PA amps.

### Accoustic Guitars 🎸
Mute guitars when they are being plugged in and unplugged. Loud pops are unplesant.

On the equalizer of the guitar, a gentle cut of about -4 dB in the 1000 hz range to make it easier to hear vocalists. You can _slowly_ drift that specific parameter back to -0 during solos without vocalists but be careful because changes to guitar sound in the middle of a song can seem unnatural.

### USB recording ⏺️
The recording can be set to record only the pastor mic channel or the entire main L/R output of the board. 

Clear out the USB if there is more than two sermons on the USB. It won't record if it runs out of space. 

Beware that you can play back recordings of a sermon from the USB. Avoid pressing **play** during a service 😱
