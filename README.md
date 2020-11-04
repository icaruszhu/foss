---
title: Flashcard and Slipbox
author: Chen Wei Zhu (BLS) a.k.a YALA
---

# Flashcard and Slipbox: A Gentle Introduction to Free and Open Source Software (FOSS) Tools for Law Students
*Dr. Chen Wei Zhu (Birmingham Law School)* 2020


## Build a Plain-Text Personal Legal Knowledge System
![markdown-plks](https://raw.githubusercontent.com/icaruszhu/pat/master/image/zhu-markdown-based-plks.png)


Figure: A Markdown-based Workflow for Building a Personal Legal Knowledge System (by Chen Zhu)

## Background

This guide is prepared for my personal tutees during our weekly online Personal Academic Tutoring (PAT) sessions due to the fact we are not able to meet face to face on campus in the midst of the [[Covid-19]][^1] pandemic. I have two groups of undergraduate tutees, one being in their first year and the other final year. Each group contains about 15 students and we meet every week via Zoom. 

This is a work in progress. It serves as a live document which records my evolving thoughts on how law students may use Free and Open Source Software (FOSS) to enhance their learning experience. It is updated and released with the version control software Git. It is also a personal reflection on my role as a legal academic (yes, Yet Another Legal Academic) who wishes to share my own experience of learning and using FOSS tools for legal research.

The repository provides supplementary materials for our weekly online tutorials. There is no need to do any preparation and I will talk and walk through each topic with live demonstration of relevant FOSS tools. 


## Flashcard: Combating the Forgetting Curve 
- What is Ebbinghaus's [forgetting curve](https://en.wikipedia.org/wiki/Forgetting_curve)? Can Ebbinghaus's experiment be replicated in your own learning environment? 
- What is the best time to revise your notes? (Of course, we need to take some notes first. For developing a sensible note-taking system in the first place, see below.) What is **spaced repetition**? Have you ever tried to use flashcards for learning a new language or anything else? 


## Niklas Luhmann & Zettelkasten ("Slipbox")

<img src="https://www.deutschlandfunkkultur.de/media/thumbs/3/3aab1a90ff5682730aedaf7ef6170fafv1_max_635x357_b3535db83dc50e27c1bb1392364c95a2.jpg?key=b15887" alt="Luhmann" style="zoom: 120%;" />

Source: https://www.deutschlandfunkkultur.de/niklas-luhmann-archiv-der-blick-in-den-zettelkasten-ist.2156.de.html?dram:article_id=445878

I first came across Niklas Luhmann's works when I was reading Teubner's book *Law as an Autopoeitic System* during a *Sociology of Law* course in Edinburgh in 2004. I even initiated a [Chinese Wikipedia entry for Luhmann]( https://zh.wikipedia.org/wiki/%E5%B0%BC%E5%85%8B%E6%8B%89%E6%96%AF%C2%B7%E5%8D%A2%E6%9B%BC). (The Chinese entry has evolved substantially ever since.) At that point, I was blissfully unaware of Luhmann's Zettelkasten ("slipbox") note-taking method.

The basic idea of the Zettelkasten method is to build a personal knowledge system by using linked atomic notes. Luhmann himself uses physical "slipboxes" to store his handwritten notes with small cards. Nowadays, it is possible to digitally implement Luhmann's method with software packages.

### Note-taking software comparison 
- Zettelkasten.de: https://zettelkasten.de/
- Zettlr:  https://www.zettlr.com/ (recommended)
- Obsidian: https://obsidian.md/
- Roam Research: https://roamresearch.com/
- Emacs Org-Roam: https://www.orgroam.com/ (work with Emacs, recommended)


## Matteo Ricci's Memory Palace

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Matteo_Ricci_2.jpHealy 

    Publications Resources Teaching Prints Blog 

g" style="zoom:30%;" />

- Who is Matteo Ricci? What is his Memory Palace technique as described by Jonathan Spence? (see Spence, *The Memory Palace of Matteo Ricci*,1985) 
- What is the [method of loci](https://en.wikipedia.org/wiki/Method_of_loci)? 
- Can you build a "digital memory palace" for your own legal studies with the note-taking system of your choice?



## Use Markdown for note-taking 
- Markdown was invented by John Gruber in 2004
  + https://daringfireball.net/projects/markdown/
  + co-author: Aaron Swarz (1986- 2014)

- There are many flavours of Markdown
  + Github Flavour  Markdown: https://github.github.com/gfm/
  + Pandoc Markdown: https://rmarkdown.rstudio.com/authoring_pandoc_markdown.html%23raw-tex
  + CommonMark: https://commonmark.org/
 
- Exercise: prepare your CV in markdown
  + a sample CV template in markdown
https://github.com/icaruszhu/student-gh-page-template/blob/gh-pages/index.md

- Video tutorials:
  +  A mardown syntax tutorial by Giraffe Academy (8 minute long) on youtube  https://www.youtube.com/watch?v=2JE66WFpaII
  +   Nicholas Cifuentes-Goodbody, Academic Writing in Markdown, 10 Dec 2016
https://www.youtube.com/watch?v=hpAJMSS8pvs


## Zotero/Juris-M
Zotero is a FOSS reference management system. Juris-M is a fork from Zotero and it is designed for better legal citations.

- Online Zotero tutorials
  + Sebastian Karcher and Rintze M. Zelle, Mastering Zotero
A user guide for the Zotero reference manager
at   https://zotero-manual.github.io/  CC-BY-SA
  + Prof. Nicholas Cifuentes-Goodbody provides one of the most lucidly explained video tutorials on how to use Zotero:
     - Tutorial: Getting Started with Zotero 4: https://www.youtube.com/playlist?list=PLXt-tu7G1H3vlRXLmGyOzeAp7ZKDK0pty

- Useful Zotero Plugins
  +  Better BibTex BBT  https://github.com/retorquere/zotero-better-bibtex
  +  Zotfile: http://zotfile.com/
  +  Zutilo: https://github.com/willsALMANJ/Zutilo

### Legal citation styles
- OSCOlA: The Oxford University Standard for Citation of Legal Authorities
  + OSCOLA official website: https://www.law.ox.ac.uk/research-subject-groups/publications/oscola
  + OSCOLA Quick reference guide (a one-page cheatsheet) https://www.law.ox.ac.uk/sites/files/oxlaw/oscola_4th_edn_hart_2012quickreferenceguide.pdf
  
  + OSCOLA csl: https://github.com/citation-style-language/styles/blob/master/oscola.csl
  
  + OSCOLA-BibLaTex by Paul Stanley QC (Essex Court Chamber): https://ctan.org/pkg/oscola?lang=en
  
- The Bluebook® : https://www.legalbluebook.com/

- The Indigo Book: https://law.resource.org/pub/us/code/blue/IndigoBook.html

- Automating legal citations
  + Zotero/Juris-M
  + OSCOLA sample at Zotero: https://www.zotero.org/groups/229950/oscola_samples/items/MD4Q6QXC/item-list

  

## Org-Roam
[Org-roam](https://www.orgroam.com/) is a brilliant Emacs package that implements Luhmann's Zettelkasten method. Although it is inspired by Roam Research (RR), I think it does much more than RR. Unlike RR (which is cloud-based at the moment), Org-Roam does everything locally on your own computer.    Of course, Org-Roam works with the versatile ```org``` files, which can be version controlled. Frankly, the learning curve for Emacs, Org and Org-Roam (which are all free software) can be steeper than other software packages, but I think the efforts of learning these FOSS tools will be rewarding eventually. 

## Pandoc
[Pandoc](https://pandoc.org/) is a universal file format converter. It is written in a functional programming language called Haskell. It is an essential tool for publishing your plain-text system into the desired format for the purpose of communicating with the rest of the world.


## Git (Version control)
- Git is Linux Torvalds' "invention" in 2005. He develops Git as an alternative to the then proprietary version control system called BitKeeper (which only becomes open source much later.) 

- Git is a superb tools that allows you to manage multiple drafts (called "versions") of your work in progress. It also allows large-scale textual collaboration that records and manages complex multi-authorial information. 

- Git can be useful for lawyers to create and manage versions of legal documents, but it is suprisingly under-used in the legal field.

## Build a Static Personal Site with Jekyll
- Jekyll allows to build your own personal static website simply by writing pages in Markdown. It saves you from writing verbose HTML code. You can use Jekyll to build your site and host your site on Github or other source code repository sites.

- *Programming Historian* provides a good tutorial here about Jekyll and Github: https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages

- I have also written a brief tutorial with a simple template for the static site of a notional law student (whose name is Temp Late)
https://github.com/icaruszhu/student-gh-page-template

## Suggested Readings

### Academic Writing with Plain Text  
- Healy, Kieran. ‘The Plain Person’s Guide to Plain Text Social Science’, (2019) https://kieranhealy.org/publications/plain-person-text/.


### Take Linked Atomic Notes
- Ahrens, Sönke. How to Take Smart Notes: One Simple Technique to Boost Writing, Learning and Thinking – for Students, Academics and Nonfiction Book Writers. 1 edition. North Charleston, SC: CreateSpace Independent Publishing Platform, 2017. 

### Version Control with Git

- Westby, Emma Jane Hogbin. Git for Teams: A User-Centered Approach to Creating Efficient Workflows in Git. 1 edition. Sebastopol, CA: O’Reilly Media, 2015.
This is the single best book I read about Git. It contains wisdom more than Git as software, but [TBC]    )

- Brett, Matthew. ‘The Curious Coder’s Guide to Git — Curious Git’, 13 February 2017. https://matthew-brett.github.io/curious-git/.

### Memory Palace
- Spence, Jonathan D. 1985. The Memory Palace of Matteo Ricci. Reprint Edition. New York, N.Y: Penguin.

### Legal Citation

- Sprigman et al., The Indigo Book: A Manual of Legal Citation, Public Resource (2016)

### Niklas Luhmann

- Luhmann, Niklas. ‘Communicating with Slip Boxes--An Empirical Account’. http://luhmann.surge.sh/communicating-with-slip-boxes (translated by Manfred Kuehn)

- Teubner, Gunther. 1993. Law as an Autopoietic System. Oxford, UK ; Cambridge, USA: Wiley-Blackwell.


## Inside a Law Students' FOSS Toolbox
- [ ] Markdown (markup language,https://daringfireball.net/projects/markdown/license)
- [ ] Zettlr (markdown editor, GPLv3)
- [ ] Zotero/Juris-M (Reference management, AGPLv3)
- [ ] Git (Version Control, GPLv2 )
- [ ] Jekyll (static site generation, MIT License)
- [ ] OBS Studio (recording and streaming video presentations,GPLv2 )
- [ ] Emacs Org-mode (markup language and more, GPLv3)


## Footnotes

[^1]: Not all markdown editors support the ```wiki-link``` syntax (i.e. ```[[some-wiki-link-text]]```). You may need to use editors such as Emacs ```markdown mode``` or ```Zettlr``` to make wiki-links work properly on your local computer.


