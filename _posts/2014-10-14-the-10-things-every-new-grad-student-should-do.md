---
title: 'The 10 Things Every New Grad Student Should Do'
date: 2014-10-14
permalink: /posts/2014/10/the-10-things-every-new-grad-student-should-do/
---

# The 10 Things Every New Grad Student Should Do

It's now mid-October, and I'm guessing that first year graduate students are knee-deep in courses, barely considering their potential thesis project. But for those that can multi-task, I have compiled this list of 10 things that you should undertake in your first year as a grad student. These aren't just _any_ 10 things… they are 10 steps you can take to make sure you contribute to a culture shift towards open science. Some a big steps, and others are small, but they will all get you (and the rest of your field) one step closer to reproducible, transparent research.

## 1\. Learn to code in some language. Any language.

Here's the deal: it's easier to use black-box applications to run your analyses than to create scripts. Everyone knows this. You put in some numbers and out pop your results; you're ready to write up your paper and get that [H-index][1] headed upwards. But this approach will not cut the mustard for much longer in the research world. Researchers _need_ to know about how to code. Growing amounts and diversity of data, more interdisciplinary collaborators, and increasing complexity of analyses mean that no longer can black-box models, software, and applications be used in research. The truth is, if you want your research to be reproducible and transparent, you must code. In a 2013 article "[The Big Data Brain Drain: Why Science is in Trouble][2]", Jake Vanderplas argues that

> In short, the new breed of scientist must be a broadly-trained expert in statistics, in computing, in algorithm-building, in software design, and (perhaps as an afterthought) in domain knowledge as well.

I learned MATLAB in graduate school, and experimented with R during a postdoc. I wish I'd delved into this world earlier, and had more skills and knowledge about best practices for scientific software. Basically, I wish I had attended a Software Carpentry bootcamp.

The growing number of [Software Carpentry][3] (SWC) bootcamps are more evidence that researchers are increasingly aware of the importance of coding and reproducibility. These bootcamps teach researchers the basics of coding, version control, and similar topics, with the potential for customizing the course's content to the primary discipline of the audience. I'm a big fan of SWC – read more in [my blog post on the organization][4]. Check out SWC founder Greg Wilson's article on some insights from his years in teaching bootcamps: [Software Carpentry: Lessons Learned][5].

## 2\. Stop using Excel. Or at least stop ONLY using Excel.

Most seasoned researchers know that Microsoft Excel can be potentially problematic for data management: there are loads of ways to manipulate, edit, reorder, and change your data without really knowing exactly what you did. In nerd terms, the trail of dataset changes is known as [provenance][6]; generally Excel is terrible at documenting provenance. I [wrote about this a few years ago on the blog][7], and we mentioned a few of the more egregious ways people abuse Excel in our [_F1000Research_ publication on the DataUp tool][8]. More recently guest blogger Kara Woo wrote a [great post about struggles with dates in Excel][9].

**Of course, _everyone uses Excel_.** In our [surveys for the DataUp project][8], about 88% of the researchers we interviewed used Excel at some point in their research. And we can't expect folks to stop using it: it's a great tool! It should, however, be used carefully. For instance, don't manipulate the sole copy of your raw data in Excel; keep your raw data raw. Use Excel to explore your data, but use other tools to clean and analyze it, such as R, Python, or MATLAB (see #1 above on learning to code). For more help with spreadsheets, see our list of resources and tools: [UC3 Spreadsheet Help][10].

## 3\. Learn about how to properly care for your data.

You might know more about your data than anyone else, but you aren't so smart when it comes stewardship your data. There are some great guidelines for how best to document, manage, and generally care for your data; I've collected some of my favorites here on [CiteULike with the tag _best_practices_][11]. Pick one (or all of them) to read and make sure your data don't get short shrift.

## 4\. Write a data management plan.

I know, it sounds like the _ultimate_ boring activity for a Friday night. But these three words (data management plan) can make a HUGE difference in the time and energy spent dealing with data during your thesis. Basically, if you spend some time thinking about file organization, sample naming schemes, backup plans, and quality control measures, you can save many hours of heartache later. Creating a data management plan also forces you to better understand best practices related to data (#3 above). Don't know how to start? Head over to the [DMPTool][12] to write a data management plan. It's free to use, and you can get an idea for the types of things you should consider when embarking on a new project. Most funders require data management plans alongside proposal submissions, so you might as well get the experience now.

## 5\. Read _Reinventing Discovery_ by Michael Nielsen.

[_ Reinventing Discovery: The New Era of Networked Science][13] _by Michael Nielsen was published in 2013, and I've since heard it referred to as the Bible for Open Science, and the must-read book for anyone interested in engaging in the new era of [4th paradigm research][14]. I've only just recently read the book, and _wow_. I was fist-bumping quite a bit while reading it, which must have made fellow airline passengers wonder what the fuss was about. If they had asked, I would have told them about Nielsen's stellar explanation of the necessity for and value of openness and transparency in research, the problems with current incentive structures in science, and the steps we should all take towards shifting the culture of research to enable more connectivity and faster progress. Just writing this blog post makes me want to re-read the book.

## 6\. Learn version control.

My blog post, [Git/GitHub: a Primer for Researchers][15] covers much of the importance of version control. Here's an excerpt:

From [git-scm.com][16], "Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later."  We all deal with version control issues. I would guess that anyone reading this has at least one file on their computer with "v2" in the title. Collaborating on a manuscript is a special kind of version control hell, especially if those writing are in disagreement about systems to use (e.g., [LaTeX][17] versus Microsoft Word). And figuring out the differences between two versions of an Excel spreadsheet? Good luck to you. The[Wikipedia entry on version control][18] makes a statement that brings versioning into focus:

> The need for a logical way to organize and control revisions has existed for almost as long as writing has existed, but revision control became much more important, and complicated, when the era of computing began.

Ah, yes. The era of collaborative research, using scripting languages, and big data does make this issue a bit more important and complicated. Version control systems can make this much easier, but they are not necessarily intuitive for the fledgling coder. It might take a little time (plus attending a Software Carpentry Bootcamp) to understand version control, but it will be _well _worth your time. As an added bonus, your work can be more reproducible and transparent by using version control. Read Karthik Ram's great article, [Git can facilitate greater reproducibility and increased transparency in science][19].

## 7\. Pick a way to communicate your science to the public. Then do it.

You don't have to have a black belt in Twitter or run a weekly stellar blog to communicate your work. But you should communicate _somehow_. I have plenty of researcher friends who feel exasperated by the idea that they need to talk to the public about their work. But the truth is, in the US this communication is _critical_ to our research future. My local NPR station recently ran a great piece called [Why Scientists are seen as untrustworthy and why it matters][20]. It points out that many (most?) scientists aren't keen to spend a lot of time engaging with the broader public about their work. However:

> …This head-in-the-sand approach would be a big mistake for lots of reasons. One is that public mistrust may eventually translate into less funding and so less science. But the biggest reason is that a mistrust of scientists and science will have profound effects on our future.

Basically, we are avoiding the public at our own peril. Science funding is on the decline, we are facing increasing scrutiny, and it wouldn't be hyperbole to say that we are at war without even knowing it. Don't believe me? Read this recent piece in Science (paywall warning): [Battle between NSF and House science committee escalates: How did it get this bad?][21]

So start talking. Participate in public lecture series, write a guest blog post, talk about your research to a crotchety relative at Thanksgiving, or write your congressman about the governmental attack on science.

## 8\. Let everyone watch.

Consider going open. That is, do all of your science out in the public eye, so that others can see what you're up to. One way to do this is by keeping an open notebook. This concept throws out the idea that you should be a hoarder, not telling others of your results until the Big Reveal in the form of a publication. Instead, you keep your lab notebook (you do have one, right?) out in a public place, for anyone to peruse. Most often an open notebook takes the form of a blog or a wiki, and the researcher updates their notebook daily, weekly, or whatever is most appropriate. There are links to data, code, relevant publications, or other content that helps readers, and the researcher themselves, understand the research workflow. Read more in these two blog posts: [Open Up][22]  and [Open Science: What the Fuss is About][23].

## 9. Get your ORCID.

ORCID stands for "Open Researcher & Contributor ID". The [ORCID Organization][24] is an open, non-profit group working to provide a registry of unique researcher identifiers and a transparent method of linking research activities and outputs to these identifiers. The endgame is to support the creation of a permanent, clear and unambiguous record of scholarly communication by enabling reliable attribution of authors and contributors. Basically, researcher identifiers are like social security numbers for scientists. They unambiguously identify you throughout your research life.

Lots of funders, tools, publishers, and universities are buying into the ORCID system. It's going to make identifying researchers and their outputs much easier. If you have a generic, complicated, compound, or foreign name, you will especially benefit from claiming your ORCID and "stamping" your work with it. It allows you to claim what you've done and keep you from getting mixed up with that weird biochemist who does studies on the effects of bubble gum on pet hamsters. Still not convinced? [I wrote a blog post a while back that might help.][25]

## 10\. Publish in OA journals, or make your work OA afterward.

A wonderful post by Michael White, [Why I don't care about open access to research: and why you should][26], captures this issue well:

> It's hard for me to see why I should care about open access…. My university library can pay for access to all of the scientific journals I could wish for, but that's not true of many corporate R&D departments, municipal governments, and colleges and schools that are less well-endowed than mine. Scientific knowledge is not just for academic scientists at big research universities.

It's easy to forget that you are (likely) among the privileged academics. Not all researchers have access to publications, and this is even more true for the general public. Why are we locking our work in the Ivory Tower, allowing for-profit publishers to determine who gets to read our hard-won findings? The Open Access movement is going full throttle these days, as evidenced by increasing media coverage (see "[Steal this research paper: you already paid for it][27]" from MotherJones, or The Guardian's blog post "[University research: if you believe in openness, stand up for it][28]"). So what can you do?

Consider publishing only in open access journals (see the [Directory of Open Access Journals][29]). Does this scare you? Are you tied to a disciplinary favorite journal with a high impact factor? Then make your work open access after publishing in a standard journal. Follow my instructions here: [Researchers! Make Your Previous Work #OA][30].

![Openness is one of the pillars of a stellar academic career. From Flickr by David Pilbrow.][31]Openness is the pillar of a good academic career. From Flickr by David Pilbrow.

[1]: http://en.wikipedia.org/wiki/H-index
[2]: http://jakevdp.github.io/blog/2013/10/26/big-data-brain-drain/
[3]: http://software-carpentry.org/
[4]: http://datapub.cdlib.org/2013/06/28/software-carpentry-and-data-management/
[5]: http://f1000research.com/articles/3-62/v1
[6]: http://en.wikipedia.org/wiki/Provenance
[7]: http://datapub.cdlib.org/2011/09/09/potentially-problematic-excel-features/
[8]: http://f1000research.com/articles/3-6/v2
[9]: http://datapub.cdlib.org/2014/04/10/abandon-all-hope-ye-who-enter-dates-in-excel/
[10]: http://cdluc3.github.io/spreadsheet-help/
[11]: http://www.citeulike.org/user/strasser/tag/best_practices
[12]: http://dmptool.org
[13]: http://press.princeton.edu/titles/9517.html
[14]: http://research.microsoft.com/en-us/collaboration/fourthparadigm/
[15]: http://datapub.cdlib.org/2014/05/05/github-a-primer-for-researchers/
[16]: http://git-scm.com/
[17]: http://www.latex-project.org/
[18]: http://en.wikipedia.org/wiki/Revision_control
[19]: http://dx.doi.org/10.1186/1751-0473-8-7
[20]: http://blogs.kqed.org/science/2014/10/06/why-scientists-are-seen-as-competent-but-untrustworthy-and-why-it-matters/
[21]: http://news.sciencemag.org/policy/2014/10/battle-between-nsf-and-house-science-committee-escalates-how-did-it-get-bad
[22]: http://datapub.cdlib.org/2012/10/30/open-up/
[23]: http://datapub.cdlib.org/2011/10/17/open-science-what-the-fuss-is-about/
[24]: http://orcid.org/
[25]: http://datapub.cdlib.org/2013/11/07/researchers-get-your-orcid/
[26]: http://www.psmag.com/navigation/nature-and-technology/dont-care-open-access-research-73577/
[27]: http://www.motherjones.com/media/2013/09/michael-eisen-plos-open-access-aaron-swartz
[28]: http://www.theguardian.com/higher-education-network/blog/2014/aug/22/university-research-publish-open-access-journal
[29]: http://doaj.org/
[30]: http://datapub.cdlib.org/2012/11/06/researchers-make-your-previous-work-oa/
[31]: https://datapub.files.wordpress.com/2014/10/8305170412_afee4daa73_z.jpg?w=656&h=436

  
