---
title: QH 400 - Spreading Dynamics
nav_exclude: True
---

# The Spread of Information

## Description, Design, Goals

Spreading dynamics can be discerned in virtually all real-world networks and systems, from infectious diseases in human contact networks to memes and news, fake or not, on social networks. A fundamental question across a range of disciplines is how such dynamics are shaped by the structure of the networks on which they occur. Of particular interest is viral spreading, where content--whether it be an orally transmitted rumor or a digitally transmitted text, image, or video--sweeps through a population by being frequently shared between individuals, leading to widespread adoption. In this course we will examine such cascades, including whether  the likelihood, size, and speed of such cascades depends as much on the nodes through which they pass (people) as the topology of the network as well as what material is passing (texts) through the nodes to instantiate the cascade.

This course offers a survey of perspectives on the spread of ideas through networks, with a principal focus on online networks. The principle behind that choice is that the latter not only amplify the spread of ideas but also offer more readily available data collection: the goal of the course is for participants to track a cascade of their own choosing, attempting to determine the topology of its course and the nature of the network which it reveals and, at the same time, instantiates.

The goal of this course is to understand how information spreads through networks: we will focus on accurate *description* with some exploration of possibilities for *prescription*--certainly the market of being able to guarantee something going viral is quite large, and while this course is not that kind of course, one of the arenas we will chart are these imagined paths to popularity, fame, and fortune.

## Texts

Most of our texts are drawn from scholarly and scientific journals or well-established periodicals that cover our topic among others.

Berger, Jonah. 2016. *Contagious*. Simon and Schuster.

## Requirements

In addition to the required texts listed in the agenda below, participants are expected to be comfortable with  Python and have a working installation on their computer. Because assignments for this course are hosted on GitHub for Education, participants will need to have a working knowledge of Git and have a GitHub account.

Mastery of the materials and methods for this course is assessed along the following lines:

**Participation** (20%) requires active engagement with the course materials through discussions and in-class activities, some of which will, I hope, be reasonably fun and also demonstrative in terms of information *flows*.

**Exams** (30%). There are three of them. They come at the expected intervals and are entirely about insuring that you have mastered the contents of the material and can apply it to the examples provided in the exams.

**Collection** (20%). Getting data is work; getting good data is hard work. But data is so important that we set aside time in the course, and reward work on it accordingly.

**Project** (30%). The course project is not a monolithic essay--though it can be if you decide that's really what you want to do. Instead, it is a portfolio, in which, yes, writing does feature, but also a (well commented) code base, a variety of outputs (including Jupiter notebook pages), and various visualizations (or auralizations or 3D realizations). The contents are ultimately up to each participant and are negotiated with the course instructor (me).

## Agenda

### Foundations

We begin our course with a bit of an excursion: we travel back in time to understand how the printing press changed the very way we think about facts and ideas and even the way we think those things get distributed and, just as importantly, authenticated. An episode from a rather dated BBC series, *The Day the Universe Changed*, does a rather good job of putting us inside the mind of a medieval person, and then demonstrating how print changed, well, everything. We watch the fourth episode, "A Matter of Fact." Then we examine how texts work--because if we consider them only to be referential, then we have entirely missed how they work. As we will explore: texts give us the power to name situations or to transact social identity.

Burke, Kenneth. 1941. Literature as Equipment for Living. In _The Philosophy of Literary Form_, 293-304. University of California Press. [URL](texts/Burke_1941.pdf).

Bauman, Richard.  1971. Differential Identity and the Social Base of Folklore.  _Journal of American Folklore_ 84/ 331: 31-41. doi:10.2307/539731.

Kirshenblatt-Gimblett, Barbara. 1975. A Parable in Context: a Social Interactional Analysis of Storytelling Performance. In _Performance and Communication_, 105-130. Ed. Dan Ben-Amos and Kenneth Goldstein. Mouton. doi:10.1515/9783110880229.105.

Bateson, Gregory. 1972. Style, Information, and Grace. _Steps to an Ecology of Mind: Collected Essays in Anthropology, Psychiatry, Evolution, and Epistemology_. University of Chicago Press.

### The Transform

Our current era is often called the digital era, and while it is, it is not the case that it was unprecedented or unheralded. After the oral-to-print transition, many societies, and their various cultures, underwent a media transition. Like print before it, media was produced by the few to distribute to the many. It did not, however, demand an additional competence like literacy. Instead, audio media like radio and records and video media like, first, film, and then later television, were in many ways consumable without any further training. While we should never assume that any representation is like real life, these media were, and are, fairly good at obscuring such boundaries, and how they do so is worth our attention.

We begin with an examination of print virality: the [Viral Texts Project](https://web.northeastern.edu/nulab/viral-texts/).

Carpenter, Edmund, and Marshall McLuhan. 1956. “The New Languages.” Chicago Review 10(1): 46–52. DOI: 10.2307/25293194.

McLuhan, Marshall. 1959. “Myth and Mass Media.” *Daedalus* 88(2): 339–48. DOI: 10.2307/20026500

Ong, Walter J. 1971. “The Literate Orality of Popular Culture Today.” In _Rhetoric, Romance, and Technology: Studies in the Interaction of Expression and Culture_. Cornell University Press. [JSTOR](https://www.jstor.org/stable/10.7591/j.cttq43nf).

This Youtube video makes a good case that [It's not about the content](https://medium.com/whither-news/what-i-learned-at-vidcon-168e26f34970#.cuwp5fl0a).

### Cascades

The first occurrence of "fake news" as an analytical term was in 1975, in an essay by two folklorists exploring how ideas and stories transited through social groups, especially those with divergent folk groups within them.

Dégh, Linda, and Endre Vázsonyi. 1975. The Hypothesis of Multi-Conduit Transmission in Folklore. Mouton.

Granovetter, Mark. 1978. “Threshold Models of Collective Behavior.” _American Journal of Sociology_ 83(6): 1420–43. [JSTOR](https://www.jstor.org/stable/2778111).

Bikhchandani, Sushil, David Hirshleifer, and Ivo Welch. 1992. “A Theory of Fads, Fashion, Custom, and Cultural Change as Informational Cascades.” Journal of Political Economy 100(5): 992–1026. [JSTOR](https://www.jstor.org/stable/2138632).

### Contents

How something cascades through a network is determined both by the individuals involved as well the material cascading through it. A lot of the material we will consider has a somewhat older name, folklore. Folklorist Lynne McNeill explains why [Folklore doesn't meme what you think it memes](https://www.youtube.com/watch?v=PBDJ2UJpKt4&feature=youtu.be&fbclid=IwAR2oH3PFzUoiIVGqZAZd1rCD4tJgR73HMX7xuKeKfUqkTIrjEdBuE9zFVDM) in this TEDxUSU talk.

A good deal of the work done by folklorists in this regard has focused on legends. The famed _Funk & Wagnalls Standard Dictionary of Folklore, Mythology, and Legend_ had the following to say about legend in 1949:

> Originally something to be read at religious service or at meals, usually a saint's or martyr's life--thus the _Golden Legend_ of Jacobus de Voragine, a collection of saints' lives. Legend has since come to be used for a narrative supposedly based on fact, with an inter-mixture of traditional materials told about a person, place, or incident. The line between myth and legend is often vague; the myth has as its principal actors the gods, and its purpose explanation. Thus the Hercules stories may be considered to some extent myth (he is semi-divine, he made the Pillars of Hercules, etc.) or as legend (Hercules was a lord living at Tiryns). The legend is told as true; the myth's veracity is based on the belief of its hearers in the gods who are its characters. Compare *local legend*. (612)

Dorst, John. 1990. Tags and Burners, Cycles and Networks: Folklore in the Telectronic Age. _Journal of Folklore Research_ 27(3): 179–90. [JSTOR](https://www.jstor.org/stable/3814251).

Dorst references the film _Style Wars_. There is both an official [Youtube video](https://www.youtube.com/watch?v=4ReyiYUPsEs), as well as a range of [unofficial videos](https://www.youtube.com/results?search_query=style+wars), one of which seems to include [outtakes](https://www.youtube.com/watch?v=4u5OY0LgE50) from the film.

Limor Shifman, Hadar Levy, Mike Thelwall. 2014. Internet Jokes: The Secret Agents of Globalization? _Journal of Computer-Mediated Communication_ 19/4,1: 727–743. [URL](https://doi.org/10.1111/jcc4.12082).

Shifman has also worked on *memes*: [this review][] will tell you more, and you can follow the leads to get access to the text. Folklorists have long worked on memes, and you might consider the results of [this search][]. There's also a video of Shifman giving a talk on [Internet Jokes](https://www.youtube.com/watch?v=OHwPAzCfjm8&feature=youtu.be&fbclid=IwAR3LLwdLC-VXKivmlGZEi_LmSf-FpjzNzxatCR1AyUF6OfqTxAc4Vay5fAM).

Stubbersfield, Joseph, and Jamshid Tehrani. 2013. Expect the Unexpected? Testing for Minimally Counterintuitive (Mci) Bias in the Transmission of Contemporary Legends. *Social Science Computer Review* 31 (1): 90–102.

### Fake News

Weiskott, Eric. 2016. Before 'Fake News' Came False Prophecy. _The Atlantic (December 27): [URL](https://www.theatlantic.com/politics/archive/2016/12/before-fake-news-came-false-prophecy/511700/).

Higgins, Andrew, Mike McIntire, and Gabriel J.x. Dance. 2016. Inside a Fake News Sausage Factory: ‘This Is All About Income.’ *The New York Times* (November 25). [URL](https://www.nytimes.com/2016/11/25/world/europe/fake-news-donald-trump-hillary-clinton-georgia.html).

Temming, Maria. 2018. People are bad at spotting fake news. Can computer programs do better? _Science News_ (July 26). [URL](https://www.sciencenews.org/article/can-computer-programs-flag-fake-news).

Murphy, G., Loftus, E. F., Grady, R. H., Levine, L. J., & Greene, C. M. 2019. False Memories for Fake News During Ireland’s Abortion Referendum. _Psychological Science_ 30(10): 1449–1459. [DOI](https://doi.org/10.1177/0956797619864887).

Evans, Timothy H. 2018. The Bowling Green Massacre. Journal of American Folklore 131(522): 460-470. [Project Muse](https://www.muse.jhu.edu/article/707452).

The entire issue of the _Journal of American Folklore_, of which Evans' essay is a part, was focused on fake news: [JAF 131/522](https://muse.jhu.edu/issue/39305).

### Mining

In this section of the course, we use Python tools to identify pages that provide links, be they web searches or a cluster of forum posts, that we then scrape using modules like . In addition, we also trial a number of modules that gather Twitter posts, such as `Tweepy`. We will then explore how to use a library like `BeautifulSoup` to break pages into only the pieces we need and store the data in useful forms like `csv` (which we will access both natively and using `pandas`) as well as `json`. We will use Jupyter notebooks to document our explorations and for sharing with others, and through these notebooks we will explore effective commenting practices and how to turn our exploratory pieces of code into an effective code base that can be used from the command line or as part of a larger stack that gets deployed in a production environment. (While the focus of this course is on data analysis and not data engineering, that doesn't mean we shouldn't ignore the connections between the two.)

### Analysis

Brady, William J., Ana P. Gantman, and Jay J. Van Bavel. 2019. Attentional Capture Helps Explain Why Moral and Emotional Content Go Viral. _PsyArXiv_  January 15. doi:10.31234/osf.io/zgd29.

And here is the study as it appeared in _Scientific American_:

Gantman, Ana P. , William J. Brady, Jay Van Bavel. 2019. Why Moral Emotions Go Viral Online:
A study of Twitter demonstrates the attentional power of certain words. _Scientific American_ (August 20). [URL](https://www.scientificamerican.com/article/why-moral-emotions-go-viral-online/).


[AI-Generated Text Is the Scariest Deepfake of All
(https://www.wired.com/story/]ai-generated-text-is-the-scariest-deepfake-of-all/). Synthetic video and audio seemed pretty bad. Synthetic writing—ubiquitous and undetectable—will be far worse.