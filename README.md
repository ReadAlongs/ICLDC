# ICLDC "ReadAlongs" Workshop Documentation

Welcome, participants of the "'Watch Me Speak!' interactive storytelling using ReadAlong Studio" workshop!  These documents will help you understand what Readalong Studio is and how to prepare for the workshop.

## Contents and links

 - ICLDC Workshop Documentation (this site)
   - [Preparing for the workshop](workshop-prep.md)
     - [Data formats](format.md)
     - [Supported languages](languages.md)
   - [Instructions for during the worksop](during-workshop.md)
   - [Troubleshooting](troubleshooting.md)
   - [Recording of the workshop](https://www.youtube.com/watch?v=9CwDCtJGl6w) (The presentation is from 0:00 to 40:30, then it's mostly silence while participant are in the break-out rooms, which were not recorded. There is a short wrap-up from 1:14:38, but the language party at the end was not recorded due to data sovereignty and privacy considerations, and the conclusion was not recorded either.)
 - The app
   - [The ReadAlong Studio Web App](https://readalong-studio.mothertongues.org/)
   - [L'appli Studio ReadAlong en français](https://readalong-studio.mothertongues.org/fr/)
   - [El Studio de ReadAlong en español](https://readalong-studio.mothertongues.org/es/) (Gracias a Jorge Rosés Labrada)
 - Providing feedback
   - [Feedback form](https://forms.gle/1HnEJ2Va4CPGhEwT9)
   - [Feature request form](https://readalongstudio-feedback-finithek.featureupvote.com/)
 - Source code
   - [ReadAlong-Studio Web app and Web-Component](https://github.com/ReadAlongs/Web-Component)
   - [ReadAlong-Studio CLI and back-end](https://github.com/ReadAlongs/Studio)
   - [g2p (Grapheme-to-Phoneme)](https://github.com/roedoejet/g2p)
 - Related publications
   - [ReadAlong studio: Practical zero-shot text-speech alignment for Indigenous language audiobooks](https://nrc-publications.canada.ca/eng/view/object/?id=fad56ec7-77a0-4e64-98e8-c3e36ce5ac1c)
   - [Gᵢ2Pᵢ: Rule-based, index-preserving grapheme-to-phoneme transformations](https://nrc-publications.canada.ca/eng/view/object/?id=de4b961d-54bf-4187-a3fc-d875ac285e79)

## What is Readalong Studio?

Readalong Studio is a program (actually a collection of programs) to help you make and view online "read-along" and "sing-along" audiobooks for language and literacy education. As the audio plays, the word currently being spoken is highlighted, and the student can click on any word to hear it pronounced in isolation.

![Screenshot of a read-along story in the Atikamekw language](images/nikikw-small.png "A read-along story from the Atikamekw language")

You give the software two things, the text of the story, and a recording of someone speaking the story aloud. Inside, the software listens to the recording and tries to guess the exact time when each word starts and stops. (If you've ever used audio software like Audacity or ELAN, imagine measuring the exact time when every word starts and stops. You could totally do this, but it takes a long time and can be tedious; it usually takes about an hour to measure a minute of speech!)  Our software's guesses aren't perfect, but it can make these guesses in seconds.

## What do I need to prepare before the workshop?

We've covered this in the [Workshop Preparation](workshop-prep.md) page.

## How about during the workshop?

Just make sure you are registered for ICLDC 2023 and [check the schedule](https://icldc8.sched.com/) to make sure you come to the right room at the right time!

