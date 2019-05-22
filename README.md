# Recommending Relevant Sections from a Web page about Programming Errors and Exceptions

Accepted Answer at CASCON 2015
-----------------------------
```
Recommending Relevant Sections from a Webpage about Programming Errors and Exceptions
Mohammad Masudur Rahman and Chanchal K. Roy
```

**Abstract:**  Programming errors or exceptions are inherent in software development and maintenance, and given today's Internet era, software developers often look at web for finding working solutions. They make use of a search engine for retrieving relevant pages, and then look for the appropriate solutions by manually going through the pages one by one. However, both the manual checking of a page content against a given exception (and its context) and then working an appropriate solution out are non-trivial tasks. They are even more complex and time-consuming with the bulk of irrelevant (i.e., off-topic) and noisy (e.g., advertisements) content in the web page. In this paper, we propose an IDE-based and context-aware page content recommendation approach that locates and recommends relevant sections of a web page by exploiting the technical details, in particular the context, of an encountered exception in the IDE. A preliminary evaluation with 250 web pages related to 80 programming errors and exceptions and comparison against one existing approach show that the proposed approach is highly promising in terms of precision, recall and F1-measure.

Experiment Data
-----------------------------
**Exception Details**
 - Stack traces (150)
 - Contextual code segments (60)

**Relevant Content Corpus**
- HTML web pages (250)
- Ground truth (HTML) (250)
- Ground truth (TXT) (250)

Working Prototype/Plug-in
--------------------
- Eclipse plug-in
- Plug-in dependencies

Please cite our work as
------------
```
@inproceedings{cascon2015masud, 
author = {Rahman, Mohammad Masudur and Roy, Chanchal K.}, 
title = {Recommending Relevant Sections from a Webpage About Programming Errors and Exceptions}, 
booktitle = {Proc. CASCON}, 
year = {2015}, 
pages = {181--190} }

```
## Something not working as expected?

Contact:  **Masud Rahman**  ([masud.rahman@usask.ca](mailto:masud.rahman@usask.ca))

OR

Create an issue from  [here](https://github.com/masud-technope/ContentSuggest-Replication-Package-CASCON2015/issues/new)