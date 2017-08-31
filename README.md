# Cirklon tl;dr

## Song page

### Change default song behavior

> Hold SONG + RUN

* auto - scenes advance only while on the SONG page
* song - scenes always advance, except in pattern edit
* work - scenes must be recalled or advanced manually

### Create a new song

> Hold SHIFT + SONG then press according encoder

### Manual scene

A manual scene allows you to have a point in a song where the patterns of a scene will repeat indefinitely until you manually advance to the next scene.

> NEXT + SCENE to manually advance

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

**P3 patterns** are good for mono synth, arp etc.

**CK pattern** are good for polyphony, drums etc.

By default, only patterns used for the current track are listed.

To list all patterns:
> SHIFT + ENTER to bring up the selection list

### P3 Pattern

#### Gang

> Hold GANG + click step ENCODERS to add ganged notes

> Click GANG to disable gang

> SHIFT + GANG to invert gang selection

> DELETE + GANG to delete gang

> GANG + hold step encoder + hold another step encoder repeats the 

> GAND + hold 2 adjacent step encoders gangs evety step

#### Slope

> Hold first step encoder + adjust value of encoder

#### Set pattern length

> LAST + BAR encoder

Then use Bar encoder to choose bar.

Or...

> REC and then MENU, turn stepencoder below "bar length" (display encoder 6); you see this option in the rec menu, when pressing rec

#### Pattern pan

> SHIFT + BAR encoder

#### Bar follow

> Click Bar and rotate

Bar encoder will be red when Bar follow is ON.

#### Bar copy

> Hold the COPY key, then press the step key for the bar you wish to copy the current bar into

#### Bar Extend and Copy

> Hold COPY, then press a step key to select a destination bar which is beyond the current last bar of the pattern

#### Set last step

> LAST + Step key (LAST key is double-click sticky)

#### Bar edit

> Click BAR

> Turn ROW encoder to chose BAR edit row

* **XPOSE** - transpose bar
* **REPS** - number of repetitions
* **GBAR** (0 or 1) - global sync option ; When active, the bar will be reset to its first step every time the global bar loops

#### Bar copy

> Go on the source bar and click BAR (to enter bar edit mode)

> Hold COPY and press step 2

Your first bar is copied to the second bar, and the bar length of the pattern set to 2.

#### Bar loops

> SHIFT + press two of the step keys in turn, to set the first and last bars of the loop section

#### Steps copy / insert

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

#### Fill patterns

Fill patterns can only be triggered in SONG, SCENE or TRACK pages.

##### Display fill options

> SHIFT + FILL

The track numbers for each track in the current bank are shown along the bottom of the display, with a block above.
Tracks which have a fill pattern assigned will have a filled-in block.
The vertical position of each block on the four lines, labelled auto, active, mute or no fill shows the fill mode for that track. Change the mode by turning the encoder above each track key.

**Fill modes for each track**

* *auto* - the fill pattern will play if the track is active (un-muted)
* *active* - the fill pattern will always play
* *mute* - the track will be muted during a fill-on
* *no fill* - the track will ignore the fill-in

**Release modes (global)**

* *key* - fill patterns play only while the FILL key is held
* *bar* - fill patterns play until the end of the next global bar
* *scene* - fill patterns play for the rest of the current scene

----

## Track values

* List track values by hitting TRACK while on the TRACK page
* 16 slots are available for each track (use SHIFT + ROW to see them all)
* **Track midi values** - controls instruments by sending midi messages
* **Track control values** - internal settings that dynamically alter pattern playback

### Adding a track midi value

> Hit INSERT 

> Select the type of value (Midi CC, track ctrl...)

> Choose proper CC

> SAVE

> Turn encoder 6 to send CC values

To add another track midi value:

> Press encoder 7

> INSERT

> Chose CC agian

> INSERT to edit the label

> ENTER

> SAVE

### Assigning Knobs A & B

> SHIFT + encoder click

> Turn know A or B to assign

### Saving Track Values

> SAVE on the track values page

> Chose where to save

> DELETE to delete a saved value

Deleting saved values works incrementally; if a saved value has been EDITed, the first press of DELETE will revert to the saved setting. A further press of DELETE will then remove the saved setting.

Deleted settings saved at the SCENE level require the SCENE to be re-saved to make their removal permanent.

### Track Control Values

Allows to change program (pgm).

Track control values:

* **quant%** - applies real-time, variable quantisation to CK patterns (0-100%)
* **note%** - transposes notes as a proportion of the interval between the note and a centre note (0-255%)
* **noteC** - sets the center note for the note% scaling control (C0-GX (G10))
* **velo%** - adjusts velocity values as a proportion of the distance from a centre velocity value (0-255%)
* **veloC** - sets the centre velocity value for velo% (1-127)
* **leng%** - scales the lenghts of notes (0-2000%)
* **tbase** - sets the spacing for the grid used by the quant% value (as tbase)
* **octave** - transposes notes by octaves (-4 to +4)
* **knob1** - the knob1 value used for knob mask and grab events in P3 patterns (0-127)
* **knob2** - the knob2 value used for knob mask and grab events in P3 patterns (0-127)

### Track mixer page

Quick access to the MIDI volume and pan controls for every track in the current bank.

> SHIFT + TRACK from the TRACK page

> Turn ROW encoder to switch from volume and pan controls

To remove a value:

> DELETE + Press track encoder

----

## Scene page

* Workscene is a temporary holding area for the values and pattern assignments that make
up a scene.
* You begin each new song in the workscene, since there will not yet be any saved scenes.
* As you save the workscene to real scenes, you will remain in the workscene.
* Each save will store the current state of the workscene as a new scene at the end of the scene list.
* Workscene cannot be renamed.

### Scene page description

#### Gbar

This is the global bar length - the length of one bar in the scene, in 16th note steps.

In song play mode, it is used along with the length value to control how long a scene will play for before advancing to the next scene.

#### Leng(th)

The scene length is the number of bars (of Gbar steps) the scene will play for before advancing to the next scene in song play mode (1-200).

**The current scene length is also used as the default length when creating new patterns.**

#### Song Adv(ance)

This option controls whether or not the scene will advance to the next scene while in song play mode.

#### FTS (Force To Scale)

With Force to Scale (FTS) active, all notes played will be forced into the chosen scale (or key signature).

#### Xpose

All patterns will be transposed by the selected value, unless the instrument option “No Xpose” is enabled, or the X-flag is set on some pattern steps.

### Saving a scene

> SAVE when on the scene page then chose a name

Once a number of scenes have been added, you can switch to song play mode by switching to the SONG page, or manually enabling song play.

Whenever you enter song play mode while in the workscene, at the end of the next global bar, the first scene of the song will be loaded and the pattern assignments and initial active/mute status of the tracks for the scene recalled.

### Mute hold

> SHIFT + SCENE

* *OFF* - mute settings are always recalled
* *Next* - for the next scene to be recalled, the current mute status will be preserved, then mute hold will revert to OFF
* *LOCK* - for all scenes recalled, the current mute status will carry over

### Scene list

The number to the right of the scene name shows the length of the scene, except for the scene currently playing. For the current scene, the value counts down, to show how many bars will play before the scene loops (or advances, if song mode is enabled). A scene set to manual advance will show a letter ‘m’ next to the length/count number.

> SCENE key from the scene page

> Double SCENE key from any other page

Show scene options / actions

> Turn value encoder to chose scene, then click MENU key

#### Scene move

TODO

#### Scene loops

TODO

#### Recall / Copy To Workscene

TODO

#### Delete a scene

TODO

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
* **Random REL** - each step is adjusted by a random offset, again in the range between knobs A and B. Multiple passes will cause a cumulative change to the stored values.

----

## Configuring the Aux Rows

TODO

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
