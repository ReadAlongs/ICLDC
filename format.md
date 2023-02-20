# Formatting requirements for the text

There are thousands of ways of representing text, and just practically we can't handle all of them.  Luckily, within the last 20 years there's been a lot of standardization of text representation that means that the software will be able to handle MOST things people throw at it.  But if you put in text from an older document (or if you're still writing your documents using the same procedures you did 20 years ago), you might run into trouble.

Basically, so long as your document is in Unicode (specifically, in the UTF-8 encoding), and it's either plain text (.TXT) or it's something like a Word document where you can copy/paste text out of it, you'll probably be fine.  

If you don't know what Unicode is, keep reading.

## What's Unicode?

First off, we need to talk about an idea called an "encoding".  Computers store everything as numbers inside, like "hello" is typically stored as the sequence of numbers 104 101 108 108 111.  (If you noticed that both the 3rd and 4th numbers are 108, that's the lowercase "L".  You're getting the hang of it!)

For a computer to store and use text, it has to know exactly what letter maps to what number.  (Think of a big chart with every letter assigned to a number.)  It used to be that different languages might use completely different charts.  For example, the chart for Danish, Norwegian, and Swedish mapped 139 to "ï", but the Icelandic chart mapped 139 to "Ð".  It even differed between different operating systems; on an old Macintosh, the Icelandic "Ð" was 220 instead.  This obviously led to a mess, and you may have had the experience of opening an old document on a modern computer and seeing complete nonsense.  

"Unicode" was a consortium, founded in 1988, to try to get all the world's languages on the same standard, and also have a robust system to add new characters so that we collectively didn't have to switch to a new standard every time we needed to add a new letter.  By the late 1990s, Unicode started to become widely adopted, and even though the resulting system is genuinely very complicated, at least we all agree on it now!

The most common Unicode encoding is called UTF-8, and that's what our software expects.  If you wrote your document recently, using modern software like Word or a modern text editor, your document is probably already in UTF-8.

## A further complication: "font hacks"

Before the Unicode revolution, official languages of European and Asian nations had official, named letter-to-number charts, that were internationally understood and built into most major operating systems.  But most languages in the world didn't have this.  

Instead, they would use another country's chart (usually the basic U.S. English chart, ASCII) and then use a special font to display those letters *as if* they were their special letters. (If you had a lot of different letters, like Cree or Inuktut Syllabics, it might even display pairs of Roman letters as single Syllabics symbols.)  We refer to this trick as a "font hack".

Have you ever encountered a problem where if you change fonts, your document starts looking like "q4kv!b'2q4'1a41 ju1' q3mcx$l"?  Or if you copy/paste into an email you get stuff like that?  Then your document probably uses "font hacks".
 
Our software isn't able to handle documents written with font hacks.  There's just no way it can know that your "q4" corresponds to some specific letter; it doesn't see what you see, it only sees the numbers underneath, and all it knows are that those numbers correspond to "q4".

If you're lucky, you may find a language-specific converter online that turns your document into Unicode.  (That would be a good thing to do anyway, because Unicode is going to be the standard for the forseeable future, and having a Unicode version of your document will make it work with a wider variety of software.)