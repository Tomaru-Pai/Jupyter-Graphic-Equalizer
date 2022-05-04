
## Project Description
    Project "Equalizer" is a modular 5-20 Band Equalizer, which can change the Amplitude of every given Band between -12db to 12db.

    Features:
        1. ) Upload your .wav File that you want to edit in the UI and normalise it to -15dB
        2. ) Visual and simplistic UI with live updates
        3. ) Change BandCount as well as EQ Mode in real time
            BandCount: 5-20 Bands (can be changed in "Variables" Category
            EQ Mode = Choose between BASS, MID or HIGH Focus
                Bass = Low Frequencies 0 - 300 Hz
                Mid  = Mid Frequencies 1000 - 4000 Hz
                High = High Frequencies 6000 - maxfreq Hz
        4. ) Apply Settings and calculate Output
            First every Band gets an .wav copy called "Band"+[Number]+".wav"
            Every Band file gets trough a lowpass and highpass filter with the previeous calculatet Values fl and fh
            Every Band gets put together again in "Output.wav"
            ProgressBar is shown to know if the programm is working
        5.) Saves Output.wav and shows a spectrum Diagram of the Output File

### Programmed by Thomas Pail
    GitHub: https://github.com/Tomaru-Pai

#### Example Audio File Credits
    Song: Dimension 
    Creator: Creo 
    Youtube: https://www.youtube.com/channel/UCsCWA3Y3JppL6feQiMRgm6Q 
    Website: https://creo-music.com/track/dimension
    Licensed under: https://creativecommons.org/licenses/by/4.0/

#### Programming
    https://ipywidgets.readthedocs.io/en/latest/examples/Using%20Interact.html
    https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20List.html
    https://en.wikibooks.org/wiki/LaTeX/Mathematics

#### Formulars and Documents for Audio
    https://www.teachmeaudio.com/mixing/techniques/audio-spectrum#upper-midrange
    https://sound.stackexchange.com/questions/14101/what-is-the-frequency-step-formula-for-10-and-31-band-eqs
    http://www.sengpielaudio.com/calculator-octave.html
    https://github.com/AllenDowney/ThinkDSP
    
#### Other Programms used
    Music editing: Audacity
    Music Download: https://github.com/yt-dlp/yt-dlp
    
#### Special Thanks
    https://www.senarclens.eu/~gerald/
