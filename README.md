# styleguide

**age**

* a five-year-old is five years old
* the five-year-old child
* we tested twenty 7–9-year-olds
* twenty children between 7 and 9 years of age

**code**

Set computer code in a monospaced font. For R and others with a C-like syntax, use parentheses on function names.

* The command `print(message)` uses the `print()` function to display text stored in the `message` variable.

**eyetracking**

**fine-grained**

**University of Wisconsin–Madison, UW–Madison**

With an en-dash.

## How to cite

Software:

* "We used the awesomesauce package (vers. 0.1.2; Mahr, 2020)."
* In RMarkdown with Pandoc, I end up using something like ``[vers. `r packageVersion("lme4")`; @lme4]``

R packages on CRAN: 

* On CRAN, check if there is a Citation section in the description. Many packages have accompanying articles, so cite them if at all possible ([lme4](https://cran.r-project.org/web/packages/lme4/citation.html) example). 
* If that fails, check the README or associated webpage for citation information. There might be citation instructions or a Zenodo badge. 
* If that fails too, use `citation("packagename")` to get a citation generated from the package description.

R:

* "We used the R programming language (vers. 3.6.1; R Core Team, 2019)."
* `citation()` produces full citation information about R.
* For reproducibility, use `getRversion()` to get the version number.
* If important computation was done on an earlier version of R—because you fit a huge model and saved the results and reload it and from it—then you should store that version number and the `sessionInfo()` with the model. Otherwise, looking up the R version dynamically will be misleading.

Standardized tests with an abbreviation:

* Put the abbreviation in the citation. 
* "We used the MacArthur-Bates Communicative Development Inventories (MBCDI; Fenson et al., 2007)."
* The front area of the technical manual is a good place to look.

Others:

* [Praat](http://www.fon.hum.uva.nl/paul/praat.html)

When in doubt:

* A citation is meant to answer four questions: Who (When). What. Where.


## Links

* [APA blog post on writing about mathematical variables circa 2011](https://blog.apastyle.org/apastyle/2011/08/the-grammar-of-mathematics-writing-about-variables.html)
* [National Center on Disability and Journalism Disability Language Style Guide](https://ncdj.org/style-guide/)
* [Serious Eats' list of banned words in food writing](https://www.seriouseats.com/2019/08/our-updated-list-of-banned-words.html). A fun example of a domain-specific style guide. You probably would recognize many food-writing cliches (*so decadent and addicting*), and many of these are banned with justification.
