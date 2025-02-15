# APIs and Libraries

## NLP Libraries

- 🔗 [RiTa](https://rednoise.org/rita/), a software toolkit for computational literature created by Daniel Howe
  - 🚨 [RiTa Basics tutorial video](https://youtu.be/lIPEvh8HbGQ)
- 🔗 [Compromise](https://github.com/spencermountain/compromise), modest natural language processing by Spencer Kelly
- 💻 [A2Z p5.js examples](https://editor.p5js.org/a2zitp/collections/oG3L-OLvGP)
- 💻 [RiTa p5.js examples](https://editor.p5js.org/rita-examples/collections/ltF2vMtaL)

## Data and APIs

### JSON

- 🔗 [Corpora maintained by tinysubversions](https://github.com/dariusk/corpora)
- 🔗 [loadJSON()](https://p5js.org/reference/#/p5/loadJSON)
- 📚 [loadJSON, fetch, promises slides](https://docs.google.com/presentation/d/1z5x5PZ0EhGxFkt488Q3edLdvY67Ptg0AH5KKmP2vE_Q/edit?usp=sharing)
- 📚 [2016 Notes and Examples](https://shiffman-archive.netlify.app/a2z/data-apis/)

### Dictionary / Lexicon / Word Finding APIs

- 🔗 [Data Muse](https://www.datamuse.com/api/)
- 🔗 [Wordnik](https://www.wordnik.com/)
- 🔗 [Wordnet](https://wordnet.princeton.edu/)

### JavaScript nuts and bolts

- 🚨 [fetch() video tutorial](https://thecodingtrain.com/tracks/data-and-apis-in-javascript/data/1-client-side/1-fetch)
- 🚨 [async / await](https://youtu.be/XO77Fib9tSI)
- 🚨 [loading JSON from API](https://thecodingtrain.com/tracks/data-and-apis-in-javascript/data/1-client-side/4-json)
- 🍿 [What is JSON? Video 1](https://youtu.be/_NFkzw6oFtQ?list=PLRqwX-V7Uu6a-SQiI4RtIwuOrLJGnel0r), [What is JSON Video 2](https://youtu.be/118sDpLOClw?list=PLRqwX-V7Uu6a-SQiI4RtIwuOrLJGnel0r)

### APIs

- 💻 [p5.js web editor code examples](https://editor.p5js.org/a2zitp/collections/cgfJWhpsE)
- 🔢 [2015 Wordnik Video Tutorial](https://youtu.be/YsgdUaOrFnQ), [wordnik docs](http://developer.wordnik.com/)
- 🔢 [2015 NY Times video tutorial](https://youtu.be/IMne3LY4bks), [nytimes docs](https://developer.nytimes.com/)
- 🍿 [Full 2019 Working with Data and APIs video series](https://thecodingtrain.com/tracks/data-and-apis-in-javascript) - 1: Client Side Basics

## Reading

- 📕 [Excavating AI: The Politics of Images in Machine Learning Training Sets](https://www.excavating.ai/) by Kate Crawford and Trevor Paglen
- 📚 [The Point of Collection](https://points.datasociety.net/the-point-of-collection-8ee44ad7c2fa#.y0xtfxi2p) by Mimi Onuoha (see: [Missing Datasets](https://github.com/MimiOnuoha/missing-datasets))
- 📚 [Introduction: Why Data Science Needs Feminism by Catherine D'Ignazio and Lauren Klein](https://data-feminism.mitpress.mit.edu/pub/frfa9szd/release/3)

## Assignment

1. Load "external" data in a browser-based text experiment. You may use the p5 [loadJSON()](https://p5js.org/reference/#/p5/loadJSON) function featured in many of the video tutorials, but this is also an opportunity to explore the JavaScript [fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) with `await` and `async` as [found in these examples](https://editor.p5js.org/a2zitp/collections/cgfJWhpsE). See above for relevant video tutorials. Here are some ideas:

   - Look through [Corpora](https://github.com/dariusk/corpora) and download JSON files for use in a p5.js sketch. For this I suggest using `loadJSON()` directly.
   - Use [RiTa.js](https://github.com/dhowe/RiTaJS) or [Compromise](https://github.com/spencermountain/compromise) to analyze and/or modify text.
   - Use an API like [Datamuse](https://www.datamuse.com/api/) or [Wordnik](http://developer.wordnik.com/) to lookup meta-data about a word.
   - Try using another API from the examples (NYTimes, Wikipedia, etc.) or pick your own not from the examples!

2. Document your experience working with the library, API, or data source in a blog post and consider the following questions (stemming from the [Excavating AI](https://www.excavating.ai/) reading.
   - What is the origin of the data?
   - Who had the power to collect, label, and make available the data?
   - If you had to create a "data biography" (Thank you to Ellen Nickles for this term), what would you include? Have the maintainers of this dataset or API made this information easily available?
   - What potential harms could result from the collection, use (or misue) of the data?

## Add your assignment below via Pull Request

_(Please note you are welcome to post under a pseudonym and/or password protect your published assignment. Here is some [helpful information on privacy options for an NYU blog](https://nyu.service-now.com/sp?id=kb_article&sysparm_article=KB0012245&sys_kb_id=b2ddc9da004aa1002a5d036a271e5f70&spa=1). Finally, if you prefer not to post your assignment at all here, you may email the submission.)_

- Name - [title](url)
- Athena - [A2Z Feud: Fast Adjectives](https://www.notion.so/athenazhou/03-APIs-2f3d3057930e4fb4b8b3b23b50182351?pvs=4)
- Kay - [NYT Article Search](https://kayitp.wordpress.com/2023/09/28/a-to-z-wk-3/)
- Cindy Wang [gibberish converter](https://rhetorical-croissant-d02.notion.site/Week3-API-Cindy-Wang-5599ea506e6d4767ad66dfc4e8b8d7e4?pvs=4)
- Oliver - [Artsy.net Artist Search](https://yuanzichen.notion.site/Week-4-API-Homework-dc2d2d3293a84e149308d42c15a800b9?pvs=4)
- Jane - [Chinese Calendar](https://janecheng.notion.site/Week-3-API-941958b6e7b84725b4fa8f410f7f9065?pvs=4)
- Tres - [Noun Replacement Update](https://www.notion.so/Portfolio-15449bb0e7bc45669086b37441295a4f?p=9deed7ec9ff945ffb72368619c3c59ab&pm=c)
- Lan - [A2Z api practice](https://yichunlan.com/A2Z-Week-3)
- Annan - [A2Z NYT API practice](https://github.com/An9Yang/NYT_title_tornado) or [p5 web editor](https://editor.p5js.org/ay2494/sketches/kslii8Y7Q)
- Joann [NYT API] (https://joannmyung.notion.site/W2-HW-New-York-Times-article-Finder-963a372ff8b74841a0c54e3ac32eab4c)

## Emoji Key for Video Tutorials, Readings, and more

- 🚨 Watch this video tutorial! (this is technical info needed for the examples). Of course if you alreaddy know this material, you can skip.
- 🔢 This is found in a group, maybe pick just one to check out!
- 🍿 Additional video if you have a particular interest and want to do a deeper dive.
- 📕 Required reading! Let's make sure we all have read this.
- 📚 Optional additional reading for a deeper dive.
- 💻 Code examples here!
- 🔗 Extra reference material / link
