<a href="https://www.buymeacoffee.com/H2wlgqCLO"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" height="21px" ></a>

# Paper writing checklist and advice

This is a checklist for academic paper writing (or peer-review). The document covers text flow, style, figures and table formatting. This document is based upon a number of references, combining the most actionable items into an easy checklist. I credit the [rOpenSci](https://ropensci.org/) code review approach for the checklist idea. A printable pdf version of this file can be [downloaded from the repository](https://github.com/khufkens/paper_writing_checklist/raw/master/paper_writing_checklist.pdf).

This checklist is not exhaustive but should cover the most important components of a well structured manuscript. I refer to the author's guide of a targetted journal for additional requirements on the manuscript layout and style elements.

## Text

### Flow

The flow or story arc of your manuscript can take on various forms, but most commonly has an hourglass. Here, the width of the hourglass refers to the scope of the material discussed, where the story line itself will fit the Opening, Challenge, Action, Resolution (OCAR) structure, which mostly reflects the standard layout of a paper (see below).

An hourglass shaped story arc starts with a broad discussion of the context in which to frame the current work, the introduction. The story arc then narrows to the scope of the research question at hand. These research questions are often put forward as formal hypothesis. These hypothesis, how to test them and the final results are layed out in the methodology and results part of the manuscript. This is the narrowest part of story arc, focussing on what is dealt with within the scope of the manuscript and little else. The story arc then widens again by discussing the results relative to (contemporary) literature only to conclude with very broad statements on how to move forward in the conclusion. Other story structures exist, but this is for sure one of the most common ones to consider.

To guide you to the process you can ask yourself a number of questions:

- Opening [O] \(Introduction)
	- &#9633; Who are the "characters" (topics covered)?
	- &#9633; What is the story about?
	- &#9633; Where does it take place (spatial / temporal coverage)?
	- &#9633; Why is the story important, what is the larger problem at hand?              

- Challenge [C] \(Introduction / Methods)
	- &#9633; What is the problem you are writing about?
	- &#9633; What specific question do you propose to answer?
	- &#9633; How ‘bad’ is it?
	- &#9633; How important?

- Action [A] \(Methods / Results)
	- &#9633; What happens to address the challenge? 
	- &#9633; Your contribution and results

- Resolution [R] \(Discussion / Conclusion)
	- &#9633; How has our world view changed as a result of A? 
	- &#9633; Big take away messages, what did you learn from your work?
	- &#9633; How should we all move forward?

Deviating from this basic structure often leads to a skewed story arcs, which either inflates expectations (funnel shape) or underplays the value of the work at hand (inverted funnel). For an in depth discussion I refer to "[Writing Science](https://global.oup.com/academic/product/writing-science-9780199760237?cc=us&lang=en&)" by Joshua Schimel.

### Language

- &#9633; Use active language
- &#9633; Avoid long sentences (12 to 17 words max)
- &#9633; Simplify your language (dead to the thesaurus)
- &#9633; Check for spelling / grammar mistakes
- &#9633; One paragraph communicates one important idea
- &#9633; Connect paragraphs and ideas in a logical order
- &#9633; Use the present tense for facts
- &#9633; Use the past tense to describe results
- &#9633; Avoid informal language, superlatives
- &#9633; Limit the use of conjuctive (connecting) words (e.g. however, moreover)
- &#9633; Limit repetitive words (don't substitute using the thesaurus, re-evaluate the sentences)
- &#9633; Don't use spoken abbreviations (e.g. it's)
- &#9633; Single-digit numbers should be spelled out; numbers of two or more digits should be expressed as numerals

### Page Layout

- &#9633; 12 point font (preferrably a serif font)
- &#9633; Double spaced lines
- &#9633; Number pages
- &#9633; Number lines continuously
- &#9633; Avoid "[widows or orphans](https://en.wikipedia.org/wiki/Widow_(typesetting))" or small parts of a larger paragraph remaining at the bottom of a previous page
- &#9633; Follow the author's layout guide of the journal, most often the schemes:
	- Introduction, Methods, Results, Discussion, Conclusion
	- Introduction, Results, Discussion + Conclusion, Methods

### Citation

- &#9633; Check citations (present in both the manuscript and the reference list)
- &#9633; Are all data and software sources cited
	- In R use the [citation()](https://www.rdocumentation.org/packages/utils/versions/3.5.1/topics/citation) function to find proper citations to packages
- &#9633; Is the measurement equipment cited
- &#9633; Check the citation style required

## Figures

- &#9633; Figure components are legible in print and on screen
- &#9633; All axis are named
- &#9633; Figures are colourblind friendly (for colour schemes see: [ColorBrewer](http://colorbrewer2.org/)) 
- &#9633; The use of symbols and line types is preferred over colour
- &#9633; The caption explains the purpose and content of the figure
- &#9633; All figures have the same axis orientation
- &#9633; Figures with the same (x/y) axis are combined in a single panel
- &#9633; Limit the number of pictures in the main manuscript
	- Additional figures can go in the Appendix

## Tables

- &#9633; The caption explains the purpose and content of the table
- &#9633; Limit the number of tables in the main manuscript
	- Additional tables can go in the Appendix

## References

[Schimel J., 2011, Writing Science: How to Write Papers That Get Cited and Proposals That Get Funded, Oxford University Press, 240p.](https://global.oup.com/academic/product/writing-science-9780199760237?cc=us&lang=en&)

[Writing a science paper some dos and don'ts](https://www.elsevier.com/connect/writing-a-science-paper-some-dos-and-donts)

[Experimental Biosciences writing science](http://www.ruf.rice.edu/~bioslabs/tools/report/reportform.html)

[11 steps to structuring a science paper editors will take seriously](https://www.elsevier.com/connect/11-steps-to-structuring-a-science-paper-editors-will-take-seriously)

Writing lab (ENV385w) notes by [Katharyn Duffy](https://github.com/katharynduffy)