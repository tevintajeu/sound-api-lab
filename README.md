## Concept
Volume doesn't stay put. While the track is playing, pressure constantly drains from the system. You have to actively click the **PUMP** button to keep the audio audible — but push too hard and the pipe bursts.

## Features
* **Core Playback:** Play / Pause with a seek bar showing current and total time.
* **Skip Controls:** Skip forward or backward by 10 seconds.
* **Playback Speed:** Adjustable speed control (0.5× to 2.0×).
* **Loop & Mute:** Quick toggles for continuous looping and muting/unmuting the audio.
* **Hydraulic Leak Mechanic:** Volume pressure continuously drains by 1% every 50ms while the track is playing.
* **Pump Button:** Injects +8% volume pressure per active click.
* **Burst Penalty:** Exceeding 105% pressure triggers heavy audio distortion (via Web Audio API `WaveShaperNode`) followed by a 5-second pump lockout.
* **Sine-Wave Volume Slider:** Drag the thumb along a live, mathematically generated SVG wave to manually set pressure.
* **Keyboard Shortcuts:** * **Space** : Play / Pause
  * **P** : Pump
  * **←** / **→** : Skip backward / forward
  * **M** : Mute
