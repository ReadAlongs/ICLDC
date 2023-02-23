# ICLDC "Readalongs" Workshop documentation

Welcome, participants of the "'Watch Me Speak!' interactive storytelling using ReadAlong Studio" workshop!  These documents will help you understand what Readalong Studio is and how to prepare for the workshop.

## [Launch the ReadAlong Studio Web App](https://readalong-studio.mothertongues.org/)

## Contents and links

 - [ICLDC Read-alongs workshop documentation (this site)](#)
   - [Preparing for the workshop](workshop-prep.md)
     - [Data formats](format.md)
     - [Supported languages](languages.md)
   - [Information for during the worksop](during-workshop.md)
 - External links
   - [The ReadAlong Studio Web App](https://readalong-studio.mothertongues.org/)
   - [The ReadAlong Studio Web App (French version)](https://readalong-studio.mothertongues.org/fr/)
   - [Feedback form](#TODO-add-this-link)
   - [Feature request form](#TODO-add-this-link)
   - [Bug reports (or is this just part of feature request?)](#TODO-add-this-link)
 - Source code
   - [ReadAlong-Studio Web app and Web-Component](https://github.com/ReadAlongs/Web-Component)
   - [ReadAlong-Studio CLI and back-end](https://github.com/ReadAlongs/Studio)
   - [g2p (Grapheme-to-Phoneme)](https://github.com/roedoejet/g2p)
 - Related publications
   - [ReadAlong studio: practical zero-shot text-speech alignment for indigenous language audiobooks](https://nrc-publications.canada.ca/eng/view/object/?id=fad56ec7-77a0-4e64-98e8-c3e36ce5ac1c)
   - [Gᵢ2Pᵢ: rule-based, index-preserving grapheme-to-phoneme transformations](https://nrc-publications.canada.ca/eng/view/object/?id=de4b961d-54bf-4187-a3fc-d875ac285e79)

## What is Readalong Studio?

Readalong Studio is software program (actually a collection of programs) to help you make and view online "read-along" and "sing-along" audiobooks for language and literacy education.  As the audio plays, the word currently being spoken is highlighted, and the student can click on any word to hear it pronounced in isolation.

![Screenshot of a read-along story in the Atikamekw language](images/nikikw-small.png "A read-along story from the Atikamekw language")

You give the software two things, the text of the story, and a recording of someone speaking the story aloud.  Inside, the software listens to the recording and tries to guess the exact time when each word starts and stops.  (If you've ever used audio software like Audacity or ELAN, imagine measuring the exact time when every word starts and stops.  You could totally do this, but it takes a long time and is very boring, it usually takes about an hour to measure a minute of speech!)  Our software's guesses aren't perfect, but it can make these guesses in seconds, saving you a ton of time.

## What do I need to prepare before the workshop?

We've covered this in the [Workshop Preparation](workshop-prep.md) page.

## How about during the workshop?

In case you missed something during the presentation or need to go into more depth about a topic, we'll be putting more detailed instructions [here](during-workshop.md).  But there's nothing there right now.

