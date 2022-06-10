# Paper writing checklist and advice

This is a checklist for academic paper writing (or peer-review). The document covers text flow, style, figures and table formatting. This document is based upon a number of references, combining the most actionable items into an easy checklist. I credit the [rOpenSci](https://ropensci.org/) code review approach for the checklist idea. A printable pdf version of this file can be [downloaded from the repository](https://github.com/khufkens/paper_writing_checklist/raw/master/paper_writing_checklist.pdf).

This checklist is not exhaustive but should cover the most important components of a well structured manuscript. I refer to the author's guide of a targetted journal for additional requirements on the manuscript layout and style elements.

## Text

### Flow

The flow or story arc of your manuscript can take on various forms, but most commonly has an hourglass shape. Here, the width of the hourglass refers to the scope of the material discussed, where the story line itself will fit the Opening, Challenge, Action, Resolution (OCAR) structure, which mostly reflects the standard layout of a paper (see below).

An hourglass shaped story arc starts with a broad discussion of the context in which to frame the current work, the introduction. The story arc then narrows to the scope of the research question at hand. These research questions are often put forward as formal hypothesis. These hypothesis, how to test them and the final results are layed out in the methodology and results part of the manuscript. This is the narrowest part of story arc, focussing on what is dealt with within the scope of the manuscript and little else. The story arc then widens again by discussing the results relative to (contemporary) literature only to conclude with very broad statements on how to move forward in the conclusion. Other story structures exist, but this is for sure one of the most common ones to consider.

To guide you to the process you can ask yourself a number of questions:

- Opening [O] \(Introduction)
	- [ ] Who are the "characters" (topics covered)?
	- [ ] What is the story about?
	- [ ] Where does it take place (spatial / temporal coverage)?
	- [ ] Why is the story important, what is the larger problem at hand?              

- Challenge [C] \(Introduction / Methods)
	- [ ] What is the problem you are writing about?
	- [ ] What specific question do you propose to answer?
	- [ ] How ‘bad’ is it?
	- [ ] How important?

- Action [A] \(Methods / Results)
	- [ ] What happens to address the challenge? 
	- [ ] Your contribution and results

- Resolution [R] \(Discussion / Conclusion)
	- [ ] How has our world view changed as a result of A? 
	- [ ] Big take away messages, what did you learn from your work?
	- [ ] How should we all move forward?

Deviating from this basic structure often leads to a skewed story arcs, which either inflates expectations (funnel shape) or underplays the value of the work at hand (inverted funnel). For an in depth discussion I refer to "[Writing Science](https://global.oup.com/academic/product/writing-science-9780199760237?cc=us&lang=en&)" by Joshua Schimel.

### Language

- [ ] Use active language
- [ ] Avoid long sentences (12 to 17 words max)
- [ ] Simplify your language (dead to the thesaurus)
- [ ] Check for spelling / grammar mistakes
- [ ] One paragraph communicates one important idea
- [ ] Connect paragraphs and ideas in a logical order
- [ ] Use the present tense for facts
- [ ] Use the past tense to describe results
- [ ] Avoid informal language, superlatives
- [ ] Limit the use of conjuctive (connecting) words (e.g. however, moreover)
- [ ] Limit repetitive words (don't substitute using the thesaurus, re-evaluate the sentences)
- [ ] Don't use spoken abbreviations (e.g. it's)
- [ ] Single-digit numbers should be spelled out; numbers of two or more digits should be expressed as numerals

### Page Layout

- [ ] 12 point font (preferrably a serif font)
- [ ] Double spaced lines
- [ ] Number pages
- [ ] Number lines continuously
- [ ] Avoid "[widows or orphans](https://en.wikipedia.org/wiki/Widow_(typesetting))" or small parts of a larger paragraph remaining at the bottom of a previous page
- [ ] Follow the author's layout guide of the journal, most often the schemes:
	- Introduction, Methods, Results, Discussion, Conclusion
	- Introduction, Results, Discussion + Conclusion, Methods

### Citation

- [ ] Check citations (present in both the manuscript and the reference list)
- [ ] Are all data and software sources cited
	- In R use the [citation()](https://www.rdocumentation.org/packages/utils/versions/3.5.1/topics/citation) function to find proper citations to packages
- [ ] Is the measurement equipment cited
- [ ] Check the citation style required

## Figures

- [ ] Figure components are legible in print and on screen
- [ ] All axis are named
- [ ] Figures are colourblind friendly (for colour schemes see: [ColorBrewer](http://colorbrewer2.org/)) 
- [ ] The use of symbols and line types is preferred over colour
- [ ] The caption explains the purpose and content of the figure
- [ ] All figures have the same axis orientation
- [ ] Figures with the same (x/y) axis are combined in a single panel
- [ ] Limit the number of pictures in the main manuscript
	- Additional figures can go in the Appendix

## Tables

- [ ] The caption explains the purpose and content of the table
- [ ] Limit the number of tables in the main manuscript
	- Additional tables can go in the Appendix

# Submission process

## Co-authors 

- [ ] Do you need to include any co-authors based on data use policies
- [ ] Ask permission to include co-authors
- [ ] Ask feedback on completed manuscripts only
	- except for those very closely involved with the analysis 

## Cover letter

- [ ] Does the manuscript fit the scope of the target journal
- [ ] Report potential conflicts of interest
- [ ] Does the letter describe the relevance & novelty of manuscript
- [ ] Keep it short (aim for half a page)!

# References

[Schimel J., 2011, Writing Science: How to Write Papers That Get Cited and Proposals That Get Funded, Oxford University Press, 240p.](https://global.oup.com/academic/product/writing-science-9780199760237?cc=us&lang=en&)

[Writing a science paper some dos and don'ts](https://www.elsevier.com/connect/writing-a-science-paper-some-dos-and-donts)

[Experimental Biosciences writing science](http://www.ruf.rice.edu/~bioslabs/tools/report/reportform.html)

[11 steps to structuring a science paper editors will take seriously](https://www.elsevier.com/connect/11-steps-to-structuring-a-science-paper-editors-will-take-seriously)

Writing lab (ENV385w) notes by [Katharyn Duffy](https://github.com/katharynduffy)
