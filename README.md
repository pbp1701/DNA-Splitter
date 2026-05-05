# DNA-Splitter
For splitting notes from samples to build on to sound board

MuddySouth Real-Tone Engine: DNA-Splitter

The DNA-Splitter is the first stage of the MuddySouth Real-Tone Engine. It is designed to reclaim AI-generated music by replacing digital artifacts with the raw, heavy timber of a physical instrument.

Instead of relying on thin, watermarked AI stems, this tool allows you to build a "DNA Library" of your actual bass guitar to provide the Earth and Pressure your tracks need.

🎯 The Objective

To take a single recording of your physical instrument and automatically slice it into high-fidelity "One-Shot" samples. These samples are then used by the Performance Player to re-execute AI blueprints with real-world wood and copper tone.

🎸 DNA Capture Pattern

To use the Splitter, record a single .wav file playing the following notes in order. This provides the "dictionary" for the system:

String 1: Low E (Top String)

Frets: 0 (Open), 1, 2, 3 (The G), 4, 5.

String 2: A String (Second String)

Frets: 0 (Open), 1, 2, 3, 4, 5.

Recording Rules:

The Domb Strike: Use a heavy thumb or pluck for a solid church-style attack.

The Ring: Let every note ring naturally for 3-4 seconds.

The Gap: Leave 2 seconds of silence between every note so the Slicer can find the edges.

🛠 Features

Visual GUI: No terminal commands. A clean interface for loading and slicing.

One-Shot Logic: Fires raw, unclipped samples for maximum depth.

Sequence Mapping: Automatically identifies and names your notes based on the capture pattern.

🚀 Setup & Requirements

This system runs on Python and requires the following libraries for AI audio analysis:

librosa (For pitch and timing analysis)

numpy (For audio math)

tkinter (For the visual interface)

Built for the McHenry Studio workflow. Reclaiming the soul of the track, one string at a time.
