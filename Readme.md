There is no intent to re-merge this code.  The text below is from the code at the time of the EATSv5 assimilation as a /vendor resource.  The intention at the time of assimilation is to use this as a base for development of a smart text disambiguation in a data-munging feedback and contextual help system.  The general idea is to use the machine to help disambiguate conversation between users and documents, and document and documents, and users and users as a form of conflation mechanism.  The expectation is that discussion will be able to be managed to plateaus of concerns around araes of concern.  For example, triage emergency associated with health issues, is "highened" and "area focused" discussion.  I would assume EMT's, etc. Triage police, fire, doctor, lawyer[criminal], peer or inter-disciplinary discussions all have best practices effectiveness and efficiency programs.  It's part of our Alice in Wonderland life that no-one but Nostradamus and a growing list of prophets could foresee.

I think people, as a general rule can be taught to see into the future further than they already do.  The first leap is to see that we are already claryoant as an unique animal species on the planet Earth, and maybe, but probably not, everywhere. That's because we are likely, I hope, to avoid being run over by the onslaught of industrial traffic we've been accumulating in a Ground-hog Day avoidance of alarm bell acknowledgement.  Ta da, innovation.  I can't help what's already started and accelerating, but I hope an inverted index system and a DSL, n-dimensional, logarithmic slide-ruler that can add and subtract, and logically figure a way to avoid infinity might be a useful way to compute and navigate in architected space-time. 

I want a frozen baseline, so I can measure distinction take form over time, and measure rates of growth, and methods of growth.  The Wordset Dictionary, as described below, will be used along with the models and modeling framework provided by Architected Futures. The 2017 base as a transfer point, if the EATSv5 effort works out, will add another point of distinction to use in surface analysis of the hull form generated over time by the modeled data.

The data munging effort will be an background task similar to "pointer checker" in RSA, which verified the integrity of relationship links buried in IMS pointers, and created reports of errors for reconiling and scrubbing. Rather than scrubbing for errors, the data is analyzed using metadata filters and models.  Contribution and effectiveness of contribution of parts toward assemblies is computed on a roll through yield basis.

Each word is an element in the EATSv5 term dictionary.  Each definition of each term, from each identified viewpoint, is also described in the dictionary, as are common intersections of words, and semantic expression symbolic maps.  Wordset dictionary words, and word-based phrases, will be able to be mapped using conceptual logic at the appropriate word, phrase, sentence, or paragraph level in a conceptually concise, accurate, precisie and effective form. 

Wordset Dictionary
==================

From 2015-2017, Wordset.org provided a public interface for anyone to help
collaborate on the world's first open source, collaborative dictionary.

However, due to... well, *cough* lack of interest... we decided to shutdown
the project.

Here we are providing the final, most up-to-date release of the Wordset
Dictionary. I'll answer some questions inline about the data and what you can
do about it.

How can I read it?
==================

The `data` folder contains a file for every letter, and one for 'misc' (that
includes emoji!).

Each file has a big JSON object keyed by the words themselves. A sample
entry might look like this:

```
{
    "largely": {
        "word": "largely",
        "wordset_id": "54bd55df7265742391cf0000",
        "meanings": [{
            "id": "54bd55df7265742391d10000",
            "def": "in large part",
            "speech_part": "adverb",
            "synonyms": ["mostly", "for the most part"]
        }, {
            "id": "54bd55df7265742391d20000",
            "def": "on a large scale",
            "example": "the sketch was so largely drawn that you could see it from the back row",
            "speech_part": "adverb"
        }]
    }
}
```

Hopefully, most of it is pretty self-explainatory.

Here's another entry that includes some labels on the meanings.

```
{
    "lindy": {
        "word": "lindy",
        "wordset_id": "54bd567d72657423915c0d02",
        "labels": [{
            "name": "American",
            "is_dialect": true
        }],
        "meanings": [{
            "id": "54bd567d72657423915e0d02",
            "def": "an energetic American dance that was popular in the 1930s, probably named for the aviator Charles Lindbergh",
            "example": "Can you lindy?",
            "speech_part": "noun",
            "synonyms": ["lindy hop"]
        }],
        "editors": ["lefurjah"],
        "contributors": ["odd_bloke", "zellerpress", "malrase", "hcatlin"]
    }
}
```

What can I use it for?
======================

Anything! We're giving this to the world. If you need a basic english Dictionary
then no sense in paying for fees, this is definitely good enough for almost
all uses.

We'd LOVE to see adapters for different languages using this. Or, if you have
an idea of something you want to do, hit us up! We're still around on the
internet and happy to help!

Is it Complete?
===============

Alas, nothing is ever complete. However, we started the project by utilizing
the Princeton WordNet project, and then made many thousands of modifications
of that. But, with 177k words, and 63,936 manual edits by volunteers it's as
complete as it will be.

What about WordNet?
===================

Most open source projects use WordNet for simple dictionary usages, but we
have vastly improved and modified that original source to be something much
more human friendly.

Also, WordNet takes a long time to grok, this is some pretty human-readable
stuff.

Did I mention that this is all in JSON?

Is It Racist/Sexist/Whatever?
=============================

We've had several projects on the site to try and mitigate some of the more,
uh, problematic entries. However, we didn't get to everything. WordNet, the
original source of the material, sourced *their* data from many different
sources. As their goal was to power machine learning and word-maps,
the definitions were often not handled with much care.

So, you can definitely find some stuff in here that we should update. In fact,
it's not too late... feel free to put in a PR if you want to edit something.
Can't guarantee we'll have a lot of time to check it out, but at least it will
be something!

Gender Neutral
==============

After several months of working on the dictionary, we realized how many stupidly
and uselessly gendered example sentences there were. We have several write-ups
about the project, but we decided to go through every single sentence that
included a gendered pronoun and re-write it.

We found this *drastically* improved the quality of the content and in almost
every case was a huge step up. "They went to the store" instead of "She went
to the store".

Editorial Guidelines
=======================

I've included the original editorial guidelines in `Guidelines.md`, but note
that since we didn't edit every word in the dictionary, that not all of them
are strictly followed.

Contributors
============

Wordset was founded by Hampton Lintorn Catlin <hcatlin> and Michael Lintorn
Catlin <malrase>, and we were joined by Justin Lefurjah <lefurjah> in making
this project a reality.

Justin, in fact, was by far our largest contributor. He was personally
responsible for 97 new words and 7,460 edits!

Also, we had a TON of volunteers, who worked for hours and hours improving
this dictionary.

Special thanks to msingle, sabreuse, bryanedu, zellerpress, luxfactaest,
lauradhahn, odd_bloke, musicchild, jessecurry, joshuabriggs, brilliantskip,
and luciankahn for all their hard work!.
