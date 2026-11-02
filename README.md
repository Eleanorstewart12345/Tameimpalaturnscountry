# Tameimpalaturnscountry
> a code prototype that reworks Tame Impala's "Feels Like We Only Go Backwards" into a country, guitar based track, written in Python in TunePad.
> TunPad link: (https://tunepad.com/project/129756)

## Table of Contents
* [General Info](#general-information) 
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project was made for the subject: Creative Coding at UTS, assessment 2.
- The project takes a psychedelic rock song and rebuilds it in a country style, using loops, nested loops and note values.
- This song was chosen as I (the creator) am a big fan of Tame Impala, and wanted to flex my creative muscles in reimagining his music.

## Technologies Used
- TunePad (Browser, project format version 2.0)
- Python (runs inside the TunPad website)

## Features
**Bass line** made from a repeating two-note loop
**Country Guitar pattern** that alternates a low base note with a higher chord note (a "boom-chick" style picking)
**Drum arrangement in sections**, each built from nested loops
- a kick and snare intro
- a main groove with a fill every fourth bar, using nested loops
- a snare build that speeds up by halving note lengths (0.5, 0.25, and 0.125 beats)
- a "boom-chick-a" country beat
- a hi-hat outro

## Screenshots
**Bass**

<img width="545" height="515" alt="Screenshot 2026-11-02 at 11 47 55 AM" src="https://github.com/user-attachments/assets/abfb6d05-576e-4a02-a532-5b7d61b1562c" />

**Acoustic Guitar**

<img width="545" height="616" alt="Screenshot 2026-11-02 at 11 48 59 AM" src="https://github.com/user-attachments/assets/10b10653-8a87-49b3-b9ba-1ee90a7d56d0" />

**Drums**

<img width="551" height="526" alt="Screenshot 2026-11-02 at 11 49 11 AM" src="https://github.com/user-attachments/assets/a0ff698b-b652-430b-8344-4cfd5c83e69b" />
<img width="523" height="356" alt="Screenshot 2026-11-02 at 11 49 25 AM" src="https://github.com/user-attachments/assets/b0cfa487-a5f0-4819-bd8c-0b1adeec1cb0" />
<img width="514" height="234" alt="Screenshot 2026-11-02 at 11 49 33 AM" src="https://github.com/user-attachments/assets/01811528-e4c1-496d-b55b-f59adccb4457" />

## Setup
The code uses Tunpad's built-in 'Play all' function, so it runs in the TunePad web browser, nota standard Python install. No other dependencies are needed.
You need:
- a web browser
- a free TunePad account

## Usage
**Option 1: Open the live project**
1. Click the live demo link at the top.
2. Press play.

**Option 2: Import the project file**
1. Log in at [tunepad.com](https://tunepad.com).
2. Import `tunepad-project/tame-impala-turns-country.json` as a new project.
3. Press play.

**Option 3: Rebuild from the code files**
1. Create a new TunePad project at 120 BPM in 4/4.
2. Add a cell for each instrument: Bass, Acoustic Guitar and Drums.
3. Copy the code from each file in `code/` into its matching cell.
4. Press play.

**Project files**
- [bass.py](https://github.com/user-attachments/files/34251747/bass.py) - bass
- [guitar.py](guitar.py) - country guitar pattern
- [drums.py](drums.py) - drum arrangement

## Project Status
Project is *complete* as a prototype for assessment 2

## Room for Improvement
Room for improvement:
- the bass line only runs for 9 beats, so it stops well before the rest of the track.
- the guitar repeats one C major pattern, it doesn't reach the level of chord changes of the original song.
- The song overall takes a different creative direction to Tame Impala's original track, the beats of the original track should have been considered more thoroughly

## Acknowledgements
- This project was inspired by Tame Impala. (2012). *Feels like we only go backwards*. On *Lonerism*. Modular Recordings.
- Code was written in TunePad, Northwestern University. https://tunepad.com
- Learning resources: Learn TunePad and the 52685 Canvas musical coding module.
- All code in this repo is my own unless marked otherwise in the comments.
- Jacinta Kieffer provided feedback on September 17th 2026 under these questions:

**1. What do I like?**
The snare build in the drums is the standout. Halving the note length each loop so it speeds up is a smart use of loops. The “boom-chick-a” section is where it really starts sounding country. Turning a psychedelic song into country is a fun idea in itself.

**2. What’s it trying to do?**
It seems to ask whether a song still feels like itself in a totally different genre. Right now the drums and guitar pattern carry the country feel. But there’s no melody yet, so it’s hard to hear the Tame Impala song in it.

**3. Progress?**
The drums are clearly the most finished part. The bass and guitar loops are much shorter than the drums, so they drop out early. It’s not clear what you’d do next. Your README’s to-do list helps, especially adding the chord progression as a list. Learn TunePad would cover most of that.

## Contact
Created by Eleanor Stewart, UTS. 
