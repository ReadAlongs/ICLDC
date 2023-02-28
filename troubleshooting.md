# Troubleshooting 

If your readalong didn't align, or the alignments were of poor quality, here are some things to check.

## Story length

It works best if the story is less than 5 minutes long.  (It can potentially handle longer, we've had people use it for stories up to 20 minutes before.  But for this tutorial, it's better if you have something short.)

## Make sure the text and audio correspond exactly

Also, be very sure that what's being said is exactly what's written.  If there's stuff in the text that the person didn't read (like page numbers, chapter titles, or translations), or stuff in the recording that wasn't in the text (like the person saying something twice or making a mistake), then our software will have trouble with it.  

Unlike a human, the software doesn't have a sense of relevance.  It can't look at something and say "Oh, that word wasn't important, it's okay that wasn't read aloud" or "That was obviously just a mistake in speaking"; it's very literal about things.  So if you ask it to align text and audio that aren't actually the same, it'll try to do exactly what you told it to, and get wrong answers or no answers at all.

## Check for numbers and symbols 

One further thing is that our software doesn't know how to pronounce numbers in your language ― it can only guess how to pronounce things made of letters.  (It doesn't know how to pronounce "634" in all the languages of the world, that would be impossibly hard to specify.  You would have to write it out as whatever 634 is in your language, like in Spanish you would have to write "seiscientos treinta y cuatro" instead.)  

It also can't know how pronounce things like "$" as whatever your word for dollar is, "%" as whatever your word for percent is, etc.

Fundamentally, think of this software as if it's someone who *doesn't* speak your language, but is reasonably smart about what letters sound like in many languages.  If I gave you the text "seiscientos treinta y cuatro dolares" and a recording of that, and asked you to tell me when exactly each word was spoken, you could totally do this even if you had never heard a word of Spanish in your life.   If I gave you the text "$634", you wouldn't be able to do it except if you spoke Spanish, you just wouldn't know what each number sounded like.  That's the situation our software is in.  

## Check for background noise

Check whether there's a lot of background noise, like a loud fan, people talking in the background, etc.  Those can mislead the software because it has trouble hearing the speech, or gets confused who it's supposed to be listening to.
