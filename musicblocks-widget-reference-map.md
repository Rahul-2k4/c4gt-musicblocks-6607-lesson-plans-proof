# Music Blocks Widget & Block Reference Map

Quick reference for educators mapping Music Blocks widgets and blocks to lesson plan activities.

---

## Core Widgets

| Widget | Purpose | Best For | Lesson Level |
|---|---|---|---|
| **Pitch-Time Matrix** | Grid-based note placement. Y-axis = pitch, X-axis = time. | Creating melodies, understanding pitch/rhythm relationship | Beginner, Intermediate |
| **Rhythm Maker** | Drum pattern creation using a grid. | Adding percussion, understanding beat subdivision | Beginner, Intermediate |
| **Pitch-Drum Matrix** | Combined pitch and drum grid. | Multi-track compositions | Intermediate, Advanced |
| **Music Keyboard** | Play notes via virtual keyboard to preview sounds. | Ear training, pitch exploration | Beginner |
| **Temperament** | Explore different tuning systems. | Advanced music theory | Advanced |
| **Oscilloscope** | Visualise waveform of generated audio. | Understanding sound physics | Advanced, Cross-curricular |

## Key Programming Blocks by Palette

### Action Palette (dark blue)

| Block | Function | Programming Concept |
|---|---|---|
| **Action** | Define a named sequence of blocks | Function/procedure definition |
| **Do** | Call/invoke a named Action | Function call |
| **Box/Value** | Store and pass a value to an Action | Parameter/variable |

### Control Palette (orange)

| Block | Function | Programming Concept |
|---|---|---|
| **Repeat** | Repeat enclosed blocks N times | Count-controlled loop |
| **Forever** | Repeat enclosed blocks indefinitely | Infinite loop |
| **If/Then** | Execute blocks if condition is true | Conditional (selection) |
| **If/Then/Else** | Execute one branch or the other | Conditional with alternative |

### Rhythm Palette (purple)

| Block | Function | Programming Concept |
|---|---|---|
| **Note Value** | Set duration of a note (1, 1/2, 1/4, etc.) | Data/property setting |
| **Tie** | Connect two notes of same pitch | State continuity |
| **Silence** | Insert a rest of specified duration | Null/absence |

### Pitch Palette (green)

| Block | Function | Programming Concept |
|---|---|---|
| **Pitch** | Set frequency/note name | Data value |
| **Transposition** | Shift all enclosed notes by interval | Offset/transformation |
| **Set Key** | Define key signature for the piece | Context/configuration |

### Drum Palette

| Block | Function | Programming Concept |
|---|---|---|
| **Drum** | Add a drum hit | Event trigger |
| **Set Drum** | Choose drum instrument/sound | Configuration |

---

## Programming Concept ↔ Music Concept Mapping

| Programming Concept | Music Concept | How Music Blocks Teaches It |
|---|---|---|
| **Sequence** | Note series / melody | Notes placed left-to-right in Pitch-Time Matrix play in order |
| **Loop** | Ostinato / drum loop | Repeat block creates musical repetition |
| **Conditional** | 1st/2nd endings | If/Then blocks change musical output based on conditions |
| **Function/Action** | Musical phrase / theme | Action block groups notes into reusable phrase |
| **Parameter** | Dynamics / articulation | Box/Value blocks let you change note properties |
| **Nested loop** | Layered rhythms | Repeat inside Repeat creates compound rhythmic structures |
| **Variable** | Note value / pitch storage | Value blocks store musical parameters for reuse |
| **Event** | Percussion hit | Drum block triggers sound at specific time |
| **Transformation** | Transposition / modulation | Transposition block shifts entire phrase by interval |
| **Concurrency** | Harmony / counterpoint | Multiple action blocks can play simultaneously |

---

## Quick Block Reference for Teachers

```
Action "name" → Do "name"     (Define and call a function)
Repeat n [...]                (Loop n times)
Note Value = 1/4              (Set note duration)
Pitch = "Sol" or "G4"        (Set note pitch)
Transposition +5              (Shift up 5 semitones)
If/Then [condition] [...]    (Conditional execution)
Drum "kick"                   (Add drum hit)
```

---

## Lesson Plan Mapping Guide

| If your lesson covers... | Use these widgets | Use these blocks |
|---|---|---|
| Basic pitch & melody | Pitch-Time Matrix | Pitch, Note Value |
| Rhythm & beat | Rhythm Maker | Note Value, Drum, Repeat |
| Song structure | Pitch-Time Matrix, Rhythm Maker | Action, Do, Repeat |
| Scales & modes | Music Keyboard, Pitch-Time Matrix | Pitch, Note Value |
| Harmony & chords | Pitch-Time Matrix | Pitch (multiple simultaneous) |
| Algorithmic music | Any widget | Repeat, If/Then, Action, Box |
| Sound & waveforms | Oscilloscope | Any note blocks |

---

*This reference map accompanies the Music Blocks lesson-plans/ directory. See lesson-plans/README.md for the full index.*
