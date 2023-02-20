# Readalong Studio Tutorial

## What's a read-along?

Read-alongs are a kind of audiobook for language and literacy education, that highlights the word being spoken to help beginner readers follow along.  You can even click on a word to hear it said in isolation.

## What to prepare in advance

Making a story into a readalong requires two things:

  * The written text of the story, in a digital text format like .TXT.  (Just having a photo of the story isn't enough, it has to be a text document of some sort.)
  * A digital audio recording of someone reading the story aloud, in .WAV or .MP3 format.  (The less background noise, the better!  If there's a lot going on in the background -- wind or machinery or other people talking -- the software often can't process it.)

If you don't have these, you can still attend the workshop; we can show you how to write/record a quick story directly in our software, just to try it out.

### What kind of stories work best?

It works best if the story is less than 5 minutes long.  (It can potentially handle longer, we've had people use it for stories up to 20 minutes before.  But for this tutorial, it's better if you have something very short.)

Also, be very sure that what's being said is exactly what's written.  If there's stuff in the text that the person didn't read (like page numbers, chapter titles, or translations), or stuff in the recording that wasn't in the text (like the person saying something twice or making a mistake), then our software will have trouble with it.  It's not smart like a human, it can't look at something and say "Oh, that word wasn't important, it's okay that wasn't read aloud" or "That was obviously just a mistake in speaking"; it's very literal about things.  So if you ask it to align text and audio that aren't actually the same, it'll try to do exactly what you told it to, and get wrong answers or no answers at all.

One further thing is that our software doesn't know how to pronounce numbers in your language -- it can only guess how to pronounce things made of letters.  (It doesn't know how to pronounce "634" in all the languages of the world, that would be impossibly hard to specify.  You would have to write it out as whatever 634 is in your language, like in Spanish you would have to write "seiscientos treinta y cuatro" instead.)  It also can't know how pronounce things like "$" as whatever your word for dollar is, "%" as whatever your word for percent is, etc.

Fundamentally, think of this software as if it's someone who DOESN'T speak your language, but it reasonably smart about what letters sound like in many languages.  If I gave you a recording of someone saying "seiscientos treinta y cuatro dolares" and that text, and asked you to tell me when exactly each word was spoken, you could totally do this even if you had never heard a word of Spanish in your life.   If I gave you that recording and the text "$634", you wouldn't be able to do it except if you spoke Spanish, you just wouldn't know what each number sounded like.  That's the situation our software is in.  

### What kind of format does the text have to be in?

The text has to be in a digital text format, such as plain text .TXT.  For a richer format like Word .DOC, you can copy/paste the text from your document into our software.  (But note you'll lose any formatting that you had.  If you had bold or italics or colors, those will be lost.)

There are some additional requirements on how special characters and fonts are handled, like that the document has to be encoded in Unicode.  If you don't know what that means, go to [this page](format.md) to learn more.

Also, it can't just be a photo or video of the document, it has to be something with copy/paste-able text.  (If you can't easily get the text out of your document, nor will our software be able to!)

### What kind of format does the audio have to be in?

Audio recordings in .WAV and .MP3 will definitely work.  Other formats *might* work but it depends on your operating system and browser.

## What languages does the software work with?

For many languages, the software should work right out of the box.  Even your language isn't one of the 30-some languages that are explicitly listed, you can set the language setting to Undetermined (und) and it can usually make good guesses about what each letter sounds like.  (This even works for many non-Roman alphabets like Cyrillic or Arabic or Syllabics.)  

However, it will generally guess based on "typical" pronunciations of those letters across lots of languages.  If you language uses familiar letters but in unfamiliar ways, the software may have trouble guessing.

For more information on what kinds of languages *do* or *don't* work well with the automatic guessing, go to the [Languages page].