# BanjoTabs
Pet project for generating bluegrass banjo cover tabs in Python 

The goal of this project is to create a set of python functions that will allow the user to create bluegrass banjo tabs
on a standard tuning banjo if given an input of a chord progression, and a melody (written as a sequence of numbers corresponsing to the Hz of the notes therein) to produce a bluegrass banjo tab of the song.


Since bluegrass banjo uses a sequnce of right-hand "rolls" of the thumb (T) plucking either the high g (g), the low D (D) or the low g (G), the index finger (I) plucking either G, or B (B) strings, and the middle finger (M) plucking either B or d.

The desired output will appear in the console as follows:

#an empty tab template of the first two beats of G chord with no melody at 4/4 time 120bpm 16th notes.

Line 1 is what the finger the right hand uses to pluck the string

 line1 = '  T I T M T I T M '
 line2  = '|------0-------0-' (high D string) d
 line3  = '|--0-------0-----' B
 line4  = '|0---------------' G
 line5  = '|--------0-------' D
 line6  = '|----0-------0---' (high G string) g
 line7 = '        G        '

where line 7 represesnts the chord of the indicated chord progression and the numbers on each line represent the fret of that string

The melody is to be written in to replace any of the fretted sixteenth notes with that of the melody.

Yikes this looks rough.
