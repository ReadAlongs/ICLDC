# Supported languages

For many languages, the software should work right out of the box.  

Even your language isn't one of the 30-some languages that are explicitly listed below, you can set the language setting to Undetermined (und) and it can usually make good guesses about what each letter sounds like.  (This even works for many non-Roman alphabets like Cyrillic or Arabic or Syllabics.)  

## What languages are specifically supported? 

At the time of writing this:

Algonquin,
Atikamekw,
Chukchi,
Danish,
English,
Finnish,
French,
Gitksan,
Gwich'in,
Hän,
Hoocąk,
Innu-aimun,
Inuktitut,
Kanyen'kéha,
Kaska,
Kwak'wala,
Michif,
Mi'kmaq,
Moose Cree,
Northern East Cree,
Northern Tutchone,
Nsyilxcən,
Ojibwe,
Plains Cree,
Raga,
Scottish Gaelic,
SENĆOŦEN,
Seneca,
Southern East Cree,
Southern Tutchone,
Swampy Cree,
Tagish,
Tlingit,
Tsuut'ina,
Upper Tanana,
Western Highland Chatino,
and Western Inuktut.

## What about languages not on this list?

The software will generally guess pronunciations based on "typical" pronunciations of those letters across lots of languages.  It'll guess that the Latin letter "S" makes a ssss sound because that's how that letter is used in most languages.  It'll guess that Cyrillic "C" and Perso-Arabic "س" are also the ssss sound for the same reasons.  

It's not always a correct guess, but ultimately, what it's trying to do with those guesses isn't that hard.  Imagine if I played you a recording of "Uyakwazi ukuthetha isiXhosa?" ("Do you speak the Xhosa language?") and asked you to identify where each word started and ended.  Would it matter if you guessed wrong what sound the "X" made?  Nah, you'd still do fine.

However, the more often this happens, the more likely it is that errors will accumulate and the results will be not quite as good.  Let's consider two example languages, Spanish and Irish Gaelic:

* Even if you don't speak Spanish, you could probably be given a word like "domingo" or "zapatos" and make a pretty good guess at how it's pronounced, because Spanish uses its letters in a pretty cross-linguistically ordinary way.  You might not be able to pronounce it correctly, but if you heard it in a recording, you could probably recognize it.

* On the other hand, consider Irish Gaelic.  If someone gave you the word "mhaith", how would you pronounce that?  It's something more like "va" or "wa"!  You would absolutely never guess that if you didn't know Irish Gaelic, and nor will our software.  

So you have to ask yourself, "Is my language more like Spanish, or more like Gaelic?"  (Actually, even Gaelic should work fine.  Enough of the letters *do* have their ordinary pronunciations that it doesn't throw things off much.  I just cherry-picked "mhaith" for an example.)

Anyway, we suggest, if your language isn't already supported by the software, to try using the Undetermined (und) setting and see how well that works.  If it works very poorly, but there's a language that's written in a very similar way to yours (e.g. a neighboring language), give that a try next.  If it doesn't work with "und", and there's no similar-enough language, send us an email after the workshop and we'll discuss adding a language-specific pronunciation chart for your language.

## Other difficult languages

Other languages that may not work well are ones where vowels aren't written and you have to figure them out based on context, like Arabic and Hebrew.  The software just isn't smart enough to add in unwritten vowels in a language it doesn't know.  

It also won't work well in languages where one symbol can have completely different readings depending on context, like in Japanese.  The software can't know when "山" is pronounced as "san" vs. "yama", let alone completely unpredictable stuff like "小豆" being pronounced "azuki" rather than "shōzu".

For languages like Arabic, Hebrew, and Japanese, there's not a whole lot we can do because learning how to pronounce sentences these languages *is* a very hard, language-specific problem that requires understanding what the sentence means in order to understand how it's pronounced.  That's a LOT harder than what our software does.  You can contact us to discuss what to do about them, but for the most part it'll involve you finding or writing a language-specific program to guess pronunciations, and it's outside of what we can realistically concentrate on.