--- 
title: "Intermediate Statistics with R"
author: "Mark C Greenwood"
subtitle: 'Version 2.1 -- Published Spring 2020'
output:
  bookdown::pdf_book: 
    keep_tex: yes
    latex_engine: pdflatex
  bookdown::html_book:
    css: toc.css
    toc: yes
    mathjax: default
  bookdown::gitbook:
    config:
      toolbar:
        position: fixed
      download: ["pdf"]
      sharing: no
documentclass: book
link-citations: yes
github-repo: gpeterson406/Greenwood_Book
bibliography:
- references.bib
- packages.bib
site: bookdown::bookdown_site
biblio-style: plainnat
header-includes:
- \usepackage{amsmath}
- \usepackage{color}
---



# Cover {-}

<img src="frontMatter/titlepage_spring_2020.png" width="656" />

<!-- \frontmatter -->

# Acknowledgments {-}

I would like to thank all the students and instructors who have provided input in the development of the current version of STAT 217 and that have impacted the choice of topics and how we try to teach them that show up in this book. Dr. Jim Robison-Cox initially developed this course using R and much of this work retains his initial ideas. The first three editions of the book were co-authored with Dr. Katharine Banner, who had a major impact on all aspects of the book as it exists today. I would also like to thank Jacob Rich, who introduced me to pirate-plots that are incorporated in the newest version. Many years of teaching these topics and helping researchers use these topics has helped to refine how they are presented here. Observing students years after the course has also impacted what we try to teach in the course, trying to prepare these students for the next levels of statistics courses that they might encounter, the next class where they might need or want to use statistics, and for potentially using statistics in the rest of their lives.

I have intentionally taken a first person perspective at times to be able to include stories from some of those interactions to try to help you avoid some of their pitfalls in your current or future usage of statistics. When I take the perspective of "we", I am referring to the team of instructors that help to deliver this material to the students. I would also like to thank my wife, Teresa Greenwood, for allowing me the time and providing support as I repeatedly work on this. Buster Greenwood (our dog) played a role in approving everything that I wrote. I would like to acknowledge Dr. Gordon Bril (Luther College) who introduced me to statistics while I was an undergraduate and Dr. Snehalata Huzurbazar (West Virginia University) that guided me to completing my Master’s and Ph.D. in Statistics and continues to be a valued mentor and friend to me.

The development of this text was initially supported with funding from Montana State University’s Instructional Innovation Grant Program with the grant *Towards more active learning in STAT 217* and version 2.1 is supported by an Open Educational Research Award from the Montana State University Library. This book was born with the goal of having a targeted presentation of topics that we cover (and few that we don’t) that minimizes cost to students and incorporates the statistical software R (and the interface RStudio) from day one and every day after that. The software is a free, open-source platform and so is dynamically changing over time. This has necessitated frequent revisions of the text. 

This is Version 2.1 of the book with this title but the sixth version of most of the content. Version 2.1 is slightly updated from version 2.0 to correct a few typos, work on recommendations and demonstrations for interpretation of p-values that are not small, and correct the discussion of partial residuals in additive models and incorporates an additional example to demonstrate them. Version 2.0 heavily re-worked how we engage with "statistical significance" and put more focus on the estimation of sizes of differences than on p-values (even though p-values still feature prominently). It contained a new section on reproducibility, engaged R-markdown as an expectation instead of an optional topic, and also incorporated partial residuals in term-plots as an additional model diagnostic tool. This text has been created by Greta Linse of Great Lines Writing and Consulting Services (https://www.greatlineswriting.com/) who ported the book into RStudio's bookdown format and tried to edit and improve the writing in the text. Any remaining errors are the responsibility of Mark Greenwood. The book was initially developed during Fall 2013 and the text has continually evolved since its creation. As always, the updated edition was primarily motivated by changes in the R software that impact the methods and results that are provided here and hopefully the code will work when you try it.

\newpage

We have made every attempt to keep costs for the book as low as possible by making it possible for most pages to be printed in black and white. The printed text is available from the Montana State University Bookstore. The text (in full color and with dynamic links) is also available as a free digital download from Montana State University’s ScholarWorks repository at https://scholarworks.montana.edu/xmlui/handle/1/2999. 

Enjoy your journey from introductory to intermediate statistics!
 
<img src="frontMatter/creative_commons_license.png" width="44" style="display: block; margin: auto;" />

This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-nd/4.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.



