# Intermediate Lesson: Loops, Actions, and Building a Composition

**Target Audience:** Grades 6–9 (ages 11–15)  
**Duration:** 2–3 class periods (90–135 minutes)  
**Music Blocks Version:** Latest stable

## Overview

Students move beyond single melodies to create structured compositions using loops and actions. They learn how the Repeat block creates musical repetition (like a drum loop) and how the Action block groups notes into reusable phrases (like a function in programming). The final project is a short ABA-form composition (statement–contrast–return).

## Learning Objectives

**Music Objectives:**
- Understand how repetition creates form and structure in music
- Use ABA form (theme, contrasting section, theme return)
- Recognise how loop counts affect phrase length

**Computational Thinking Objectives:**
- Understand loops as a way to repeat instructions without copying blocks
- Understand actions as user-defined procedures (functions)
- Trace program flow through nested loops and action calls

## Prerequisites

- Beginner Pitch-Time Matrix experience (Music Blocks #6607 Beginner Lesson or equivalent)
- Basic familiarity with placing notes and changing durations

## Materials & Music Blocks Widgets

- [Music Blocks (browser)](https://musicblocks.sugarlabs.org/)
- **Widgets:** Pitch-Time Matrix, Rhythm Maker
- **Key Blocks:** Repeat block, Action block, Note Value block, Pitch block, Do block
- Optional: Printed ABA form worksheet

## Step-by-Step Instructions

### Step 1: Create a Short Melody Phrase

1. Open Music Blocks and create a new project.
2. Using the Pitch-Time Matrix, place 4 notes in the first four columns to create your "A" theme.
3. Use varied note values (quarter, half, eighth notes) to give your phrase rhythmic interest.
4. Play it back. This 4-note phrase will be your **A section**.

### Step 2: Turn Your Phrase into a Repeat Loop

1. Find the **Repeat** block in the Control palette (orange blocks).
2. Drag a Repeat block and set its count to **3**.
3. Connect your melody blocks inside the Repeat block.
4. Now when you play, Music Blocks will repeat your 4-note phrase three times — a 12-note phrase.

**Teacher tip:** Ask students to predict how many total notes will play. (4 notes × 3 repeats = 12 notes.)

### Step 3: Create an Action Block for Your A Theme

1. Find the **Action** block in the Action palette.
2. Name your Action block something like `themeA`.
3. Move the Repeat block (containing your melody) inside the Action block `themeA`.
4. Use a **Do** block to call your action.
5. Play to verify it sounds the same.

### Step 4: Build a Contrasting B Section

1. Create a second Action block named `themeB`.
2. Inside it, build a contrasting melody using:
   - Different note values (e.g., mostly eighth notes for a faster feel)
   - Different pitch range (higher or lower than themeA)
   - A different Repeat count (e.g., 2 instead of 3)
3. Call `themeB` after `themeA` using another Do block.

### Step 5: Assemble ABA Form

1. Arrange your composition blocks in this order:
   - Do `themeA`
   - Do `themeB`
   - Do `themeA` (the return)
2. Play the full ABA composition.
3. Discuss: the return of A gives the piece a sense of closure.

### Step 6: Add a Rhythm Track

1. Use the **Rhythm Maker** widget to add a drum pattern.
2. Create a simple steady beat for section A and a varied beat for section B.
3. Play the full composition with drums.

## Discussion Prompts

- Why use an Action block instead of copying the same notes multiple times?
- What changed when you increased or decreased the Repeat count?
- How does the ABA form feel different from playing notes straight through?
- What does a **nested loop** mean? (Hint: a Repeat inside another Repeat.)

## Assessment Criteria

| Criteria | Beginning (1) | Developing (2) | Proficient (3) | Exemplary (4) |
|---|---|---|---|---|
| Loop usage | Uses Repeat block once | Uses Repeat block with different counts | Uses Repeat in multiple sections | Uses nested Repeat blocks intentionally |
| Action blocks | Creates one Action block | Creates named Action blocks | Uses 2+ Action blocks with Do calls | Organises entire composition with reusable Actions |
| ABA form | A section recognisable | A and B sections present | Clear ABA structure with return | ABA structure with intentional contrast and return effect |
| Rhythm | Adds drum track | Drum track matches A section | Drum pattern changes between A and B | Drum pattern supports form (steady in A, varied in B) |

## Extension Activities

- **Parameterise the action:** Can you pass a different Repeat count to your action using a **box** or **value** block?
- **Rondo form:** Extend to ABACA form by adding a C section.
- **Ensemble:** Combine two students' compositions — one plays themeA while the other plays themeB simultaneously.
- **Cross-curricular:** Map the ABA form to a three-paragraph essay structure (introduction–body–conclusion).

## Reference Links

- [Action Block documentation](https://github.com/sugarlabs/musicblocks/blob/master/guide/README.md)
- [WhyMusicBlocks.md — Actions as Functions](https://github.com/sugarlabs/musicblocks/blob/master/WhyMusicBlocks.md)
- [Example: Mexican Music Chord Progression](https://musicblocks.net/2026/03/25/mexican-music-chord-progression/)
- [Example: La Cucaracha](https://musicblocks.net/2026/03/21/la-cucaracha/)

---

*Part of Music Blocks lesson-plans/. Intermediate level.*
