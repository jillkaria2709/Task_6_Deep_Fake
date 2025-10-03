# Sophie Hart Interview Video Project

## Overview

This project demonstrates a short AI-generated interview video featuring a fictional pop artist, **Sophie Hart**, with **pink hair** and a bold, pop-inspired style. The video includes both the **host** and **Sophie**, with **natural facial expressions** and **voice-over** generated via AI text-to-speech.

## What I Needed to Download / Tools Used

* **AI Text-to-Speech**: To generate realistic voices for both the host and Sophie.

  * Tried: Google Cloud TTS, Resemble.AI, Coqui TTS.
* **AI Video / Facial Animation**: To animate characters and sync their lips with speech.

  * Tried: Avatarify, First-Order Motion Model, VEED.io Text-to-Video.
* **Assets**:

  * Source images for Sophie (with pink hair) and host.
  * Scripts for the interview dialogue.

## What I Tried

1. Generated separate audio files for the host and Sophie Hart using various TTS engines.
2. Created facial animations using Avatarify and First-Order Motion Model.

   * Faced issues with exaggerated or creepy smiles, adjusted animation intensity.
3. Merged audio and video using `moviepy` to synchronize voices with facial movements.
4. Tested prompt variations to improve TTS flow (removed extra punctuation to fix unnatural pauses).
5. Experimented with script length and style to fit an 8–10 second video clip.

## What I Did

* Wrote a concise interview script for a short 8-second clip:

  * Host asks: "Sophie, your music has been inspiring so many people. Tell us what message you want your fans to take away"
  * Sophie responds: "Music is all about empowerment. I want my fans to feel confident and know they’re never alone"
* Created a single, comprehensive AI prompt combining:

  * **Voice details** (host neutral, Sophie energetic and empowering)
  * **Appearance details** (host professional, Sophie pink hair & crazy pop style)
  * **Facial animation cues** (natural expressions, subtle smiles)
* Generated final video with synchronized audio and facial animation.

## Notes / Lessons Learned

* Removing punctuation like full stops and curly quotes improved TTS naturalness.
* Facial animation models exaggerate expressions; tuning intensity is critical.
* Short scripts work best for AI video generators to avoid unnatural pauses.
* Combining voice and animation in a single prompt improves consistency across characters.
