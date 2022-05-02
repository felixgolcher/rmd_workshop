# Writing Reproducible Research Papers with R Markdown

## Origin

This repository was forked from [Resul Umit](https://github.com/resulumit/rmd_workshop).

He created the materials for a workshop on writing reproducible research papers with R Markdown, first taught at [Campus Luzern](https://www.campus-luzern.ch/) in March 2020.

Felix Golcher adapted for a workshop held for the [CRC 1412 *Register*](https://sfb1412.hu-berlin.de/).

This material is published under [CC-BY-SA 3.0](https://github.com/resulumit/rmd_workshop/blob/master/LICENCE.md). An easy to read summary of this permissive licence is available on the [Creative Commons website](https://creativecommons.org/licenses/by-sa/3.0/).

## Contents

The workshop is divided into ten parts. Most parts include exercises &mdash; 40+ in total.


|[]() |      |
|------|------|
| **Part 1. Getting the Tools Ready** <br /> - e.g., downloading course material | **Part 6. The R of Rmarkdown: Code Chunks and Inline Code** <br /> - e.g., plotting data | 
| **Part 2. Introducing R Markdown** <br /> - e.g., creating a new document | **Part 7. Addressing Functionality Gaps** <br /> - e.g., adjusting line spacing | 
| **Part 3. Setting Metadata** <br /> - e.g., defining output format | **Part 8. Using Version Control** <br /> - e.g., integrating Git and GitHub | 
| **Part 4. Writing Text** <br /> - e.g., adding emphasis to text | **Part 9. Collaborating with Others** <br /> - e.g., working simultaneously with co-authors | 
| **Part 5. Managing References** <br /> - e.g., citing sources | **Part 10. Working on a Real Project** <br /> - e.g., converting a work-in-progress of yours |

The parts

* Part A. Cache Functionality
   - don't recompute everything with every compilation
* Part B. Reusing Code
   - e.g., building up figures, child documents
* Part C. Fancy Templates
   - e.g., producing publication ready papers

are not yet produced. A exists as an idea only, there are exercises for B and C is essentially done by showing people the `rticles` package.

At the moment the parts are quite different in size.

I got through part 6 and a bit of Part B. in 3 days a 120 Minutes.


##  Exercise Branch

Exercises and solutions can be found in the `exercises branch`.

## Files and directories.

Below are the workshop materials kept in this repository.

- `presentation/rmd_workshop.Rmd`: an R Markdown file behind the slides, produced with the `xaringan` package (Xie, 2020)
- `presentation/data`: containing some example data on journal statistics.
- `presentation/image`: static images used in the `Rmd` file.

 
## References

Blair, G., Cooper, J., Coppock, A., Humphreys, M., Rudkin, A. and Fultz, N. (2019). [fabricatr: Imagine your data before you collect it](https://cran.r-project.org/web/packages/fabricatr/index.html). R package, version 0.10.0.

Gagolewski, M. (2020). [stringi: Character String Processing Facilities](https://cran.r-project.org/web/packages/stringi/index.html). R package, version 1.4.6.

Wiernik, B. M. (2020). [American Psychological Association 7th edition (no ampersand)](https://www.zotero.org/styles/apa-no-ampersand). Citation style language file, version 1.0.

Xie, Y. (2020). [xaringan: Presentation Ninja](https://cran.r-project.org/web/packages/xaringan/index.html). R package, version 0.18.
