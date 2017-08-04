# Cirklon tl;dr

## Song page

### Change default song behavior

> Hold SONG + RUN

* auto - scenes advance only while on the SONG page
* song - scenes always advance, except in pattern edit
* work - scenes must be recalled or advanced manually

### Create a new song

> Hold SHIFT + SONG then press according encoder

----

## Track page

### Assign an instrument

* Turn VALUE up to instrument "---"
* Press ENTER to access the instrument list
* Select create new or choose an existing instrument

### Delete an instrument

* Display instrument list
* Hit DELETE to remove it
* Confirm

If the instrument is used in a song you will be prompted to choose an alternative instrument.

### Mute a track

* Click its track button to switch status
* LED below the track reflects if a pattern is present on this track:
  * If a pattern is assigned to a muted track, the LED below the track key will
light green.
  * If a track has been set active, but no pattern is assigned, so the key LED will
be lit at half brightness.

### Arm a muted track

> Hold SHIFT + <track key>

### Edit instrument associated to a track

> When on instrument list, SHIFT + ENTER

### Delete an instrument

> When on instrument list, press DELETE

### Create /list patterns

* Use VALUE to highlight the PATTERN field
* Press ENTER to list / create patterns associated with the current track
* Or press SHIFT + ENTER to list patterns associated with all tracks

----

## Pattern page

By default, only patterns used for the current track are listed.

To list all patterns:
> SHIFT + ENTER to bring up the selection list

### Pattern types

#### P3 patterns

Good for mono synth, arp etc.

#### CK pattern

Polyphonic, drums etc.

### Pattern edit

### Set pattern length

> LAST + Bar encoder

Then use Bar encoder to choose bar.

### Bar follow

> Click Bar and rotate

Bar encoder will be red when Bar follow is ON.

### Bar copy

> Hold the COPY key, then press the step key for the bar you wish to copy the current bar into

### Bar Extend and Copy

> Hold COPY, then press a step key to select a destination bar which is beyond the current last bar of the pattern

### Set last step

> LAST + Step key (LAST key is double-click sticky)

### Bar edit

> Click Bar

> Turn ROW encoder to chose BAR edit row

* **XPOSE** - transpose bar
* **REPS** - number of repetitions
* **GBAR** (0 or 1) - global sync option ; When active, the bar will be reset to its first step every time the global bar loops

### Bar loops

> SHIFT + press two of the step keys in turn, to set the first and last bars of the loop section

### Steps copy / insert

**Copy steps**

> COPY key
> Press the first step of the section to be copied
> Then press the last step of the section to be copied

You can use BAR encoder to move to another bar

**Paste steps**

> INSERT
> Use VALUE encoder to filter what values should be pasted

To insert the selected values into the pattern, press the step key where the first step in the clip should be written.

The full length of the clip will over-write each step from that point on.

If the end of the pattern is reached before the full clip has been inserted, insertion will wrap to the start of the pattern and continue.

When copying steps to the clipboard, if you select a last step before the first step, the selected steps are copied to the clipboard in reverse order. Small sections, or the pattern can be reversed in this way.

----

## Sculpting and randomizing

The sculpt feature allows you to use knobs A and B to continuously edit the values of a pattern as it plays.

### Enable sculpt

> SHIFT + SCULPT

> SCULPT + A/B rotation

### Sculpt modes

> Press VALUE then select

* **Sculpt ABS** - the position of knob A will over-write the value in each playing step.
* **Sculpt REL** - the position of knob A will adjust the stored value by a relative amount. This can be a positive or negative offset, with zero effect at the mid-position of the knob.. If you hold SCULPT as the pattern repeats, each step will move incrementally further from its original value.
* **Random ABS**  - each playing step value will be over-written with a value randomly chosen from the range of values set by knobs A and B. It doesn’t matter whether knob A or B is greater.
* **Rndom REL** - each step is adjusted by a random offset, again in the range between knobs A and B. Multiple passes will cause a cumulative change to the stored values.

----

## Configuring the Aux Rows

TODO

----

## CK patterns

TODO

----

### Gang

### Slope

> 

### Fill patern

**Fill-in can only be triggered while on the SONG, SCENE or TRACK pages.**

#### Show fill-in options

> SHIFT + FILL

* auto - fill pattern will play if the track is active (un-muted)
* active - the fill pattern always play
* mute - the track will be muted during a fill-on
* no fill - the track will ignore the fill-in

##### Fill release options

> Use VALUE encoder to change release option

key - fill patterns play only while the FILL key is held
bar - fill patterns play until the end of the next global bar
scene - fill patterns play for the rest of the current scene

----

## Navigation

### Switch current track

In SONG, SCENE and TRACK mode:

* Click track encoder or
* Turn BAR encoder

## Naming things

* Move around with VALUE encoder
* DELETE to delete char before cursor
* Hold SHIFT to enter upper case letters
* ROW toggles between letters and numbers
* INSERT toggles between new char / over-write
* ENTER to save
* MENU to exit without saving

----

## Global configuration

### Tempo

> VALUE encoder to enter edit mode

> SHIFT + VALUE to adjust coarser or finer steps

> Tap SCULPT to set a manual tempo

> While tempo is edited, hit SAVE to save for SONG or SCENE

* When a song has a stored tempo, the label [SONG] will appear below the value.
* You can remove the stored value by pressing the DELETE key while the tempo value is edited.

### Using more than 16 tracks

Can have up to 16, 32, 48, or 64 tracks.

----

## Other

### Audition

This is useful feature if you are editing a P3 pattern while playback is stopped. If you hold a step encoder, then press the step key below it, the note value on that step will be sent to the assigned instrument, so you can confirm the note selection by ear.
