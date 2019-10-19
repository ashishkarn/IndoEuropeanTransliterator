# IndoEuropeanTransliterator
A Generalized Transliteration tool for Indo-European languages.

# The Prerequisites:

 - What does a language actually consist of?
	 - A script of finite size
	 - A dictionary of words morphed by the script
	 - Morphological rules to construct words(e.g- sandhi, schwa deletion etc.)
	 - Syntax to create Sentences
	 - Semantics to enforce 'meaning' to a sentence
	 - Phonological rules to enforce proper sounds to words(phonetic, non-phonetic, hybrid languages.)
	 - And more..

Languages make Humans human. They come in every form or way possible written, spoken, symbolic, dravidian, indo-aryan, felt, touched, conveyed, arbitrary, productive, creative, systematic, vocalic, social, non-instinctive, conventional etc. You get the idea. 

We study these languages, we rationalize them into structures and call ourselves Linguists who studied Linguistics. We as computer scientists describe computational models to describe these structures(syntax, semantics, lexemes, morphs, cognates etc.)
and call it Computational Linguistics(ML, NLP, Machine translation(9th century AD algorithm to translate Indic literature to equivalent Arabic literature)). This study is time unbounded. Since the dawn of time we have create tools and techniques to analyze languages (latest being using ML/NLP techniques and the earliest being two african tribes pointing at things to describe a thing and corroborate it with a word in their language.) and apply that knowledge to create rules for translation between languages, transliteration etc. 

Our job as humans is to continue doing what our ancestors did with the tools that we possess.

# Understanding the difference between Translation and Transliteration

Translation is a function of semantics and syntax(and some parts morphology), while 
Transliteration is a function of phonology and morphology.

 - Transliteration means generating a pronounceable word in a script that when pronounced in another language's script produces a sound equivalent to the transliterated word.
 - While translation is mapping the meaning of a word or a sentence derived from it of one language to another language structure with an equivalent meaning.
 - The Translation of "My dog ate my shoes" from English to Hindi would require analyzing the morphemes(My, dog, ate, my, shoes), mapping them to equivalent Hindi words from the Hindi dictionary, putting the words together using proper grammar and analyzing if the semantics of the sentence are correct in Hindi or not.
 - Transliteration of the same sentence would just require us to find out the words in Hindi that produce the same sound as when pronouncing the sentence in english.
 
 Note: Since English is a non-phonetic language and Hindi is a phonetic language with schwa deletion, the conversion from English to Hindi would produce a non exact result with several possibilities. For example, pronounce the word Djikstra. Did you pronounce any of these (डिज्कस्ट्रा, दजिकसत्र, द्जिकस्तरा, द्जिकसत्र ). 

Btw these are the results of the google transliteration tool. We will talk about challenges faced during Transliteration later. 

# The Later is Now
The biggest challenge I've noticed is that during translation we have finite set of words in both the source and output languages that we have to work upon. This is not the case in Transliteration. Take the example above, neither Djikstra nor डिज्कस्ट्रा are part of English and Hindi dictionaries, Djikstra is a name of Dutch origin, obviously the system of our minds transliterated the word from Dutch to English and was given to us to transliterate it to Hindi.

The second biggest challenge is also a testament and a failure of the west to acknowledge that Indian languages are superior to the "Maggi Masala" they came up with. For example the parent of most Indo-Iranian languages present right now, Sanskrit is completely phonetic. What that means is, *what you write is what you pronounce*. Let's take an example of an English word "Example". You pronounced it एक्साम्पल . Now pronounce Sample, सैम्पल . Saw, सौ . Each of these words contain the letter 'a', but the sound of it changes with accordance to the word.

While in a phonetic language like Sanskrit, every word ever written is pronounced the same way it's letters are pronounced. एक्साम्पल , सैम्पल, बादल . All these words have the letter ल which is pronounced the same way irrespective of the word. 

What it means to us Computer programmers? What it means is that, in Hindi, we assign a sound to each letter of the script. Give the program any word and it can pronounce it correctly. While in English, the program has to have information about the Word to pronounce it. And there are millions of words. Bharatvaasis have always been smart and this a testament to that fact.

# The Indo-European Scope
What is Indo-European and why are we trying to scope more than two languages?

Wiki- The **Indo-European languages** are a [language family](https://en.wikipedia.org/wiki/Language_family "Language family") of several hundred related [languages and dialects](https://en.wikipedia.org/wiki/List_of_Indo-European_languages)

You all have heard your chacha and mama talk about how Sanskrit/Tamil/bla/bla is the father/mother of all languages(which ain't that true or false) because some words are pronounced the same way or some grammar rules for languages are same. Well this is why. Indo-European languages come from Proto-Indo-European languages which were spoken by a huge tribal group based on Nomadic Steppes. Indo-aryan are a subgroup of Indo-European.

https://en.wikipedia.org/wiki/Indo-European_languages#/media/File:Indo-European_branches_map.svg

These languages are part of the same family. They have a lot of similarities like grammatic rules, sentence structuring, loan words, cognates etc. So next time you make fun of someone speaking bhojpuri, remember how it belongs to the same family of languages as French, that you spoke while imagining romancing your love on top of Eiffel Tower.

There is a lot to talk about language families and their similarities and differences that I won't do.

https://en.wikipedia.org/wiki/Indo-European_languages

And, why are we trying to scope more than two languages?
Because it's hard.

# Application

First of all, Google's transliterator is not good at all. That's why they have a 'try'.
https://www.google.co.in/inputtools/try/

You have seen the Boards where they have a place's name in multiple languages. That is one area for use of this. 
Also my dadaji would appreciate a good hindi transliterator.
# Tools and Techniques

 1. AI/ML/NLP/Bla/bla
 2. The power of Youth
 3. Passion of love and friendship
 4. Coffee
 5. Chemical X

