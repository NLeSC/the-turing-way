# Checklist

## Summary
Here we provide a short checklist for software projects. The rest of this chapter elaborates on the various point in this list.

## The list

The __bare minimum__ that every software project should do, from the start, is:
* Pick and include an [open source license]( /open_research/02/softwarelicenses).
* Use [version control](/version_control/version_control).
* Use a [publicly accessible](/open_research/02/opensourcesoftware) version control repository.
* [WIP] Add [documentation describing the project]().


We recommend that you also do the following (from the start of the project):
* Use [code quality tools](/code_quality/code_quality).
* [Testing](/testing/testing).


Additional steps depend on the goal of the software (zero or more can apply):
* [I'm publishing a paper](#im-publishing-a-paper).
* [I'm expecting users](#im-expecting-users).
* [I'm expecting contributors](#im-expecting-contributors).

## I'm publishing a paper

* [Make your software citable](/software_checklist/01/making_software_citable).
* Cite DOI in paper (see the "[Further reading](#further-reading)" section at the end of the chapter).
* Add a `CITATION.cff` file (see the "[Further reading](#further-reading)" section at the end of the chapter).


## I'm expecting users

* [Release](/software_checklist/02/releases) your software.
* [WIP] Provide [user documentation](/software_documentation/02/project_documentation).
* Provide [easy installation](/software_checklist/02/releases#one-command-install).
* Provide issue tracker.

## I'm expecting contributors

* [WIP] Provide [development documentation](/software_documentation/02/code_documentation).
* Provide a means of communication: i.e. use Github issues, mailing list, not private email.
* Implement and add a [code of conduct](/collaborating_github/3/getting_contributors#code-of-conduct).
* Add a [contribution guideline](/collaborating_github/3/getting_contributors#code-of-conduct).


## Further reading
- [1. Best Practices for Scientific Computing
](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745).
- [2. Four simple recommendations to encourage best practices in research software](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5490478/).
- [3. Software citation principles](https://www.force11.org/software-citation-principles).
- [4. Citation file format homepage](https://citation-file-format.github.io).
- [5. A standard format for CITATION files](https://software.ac.uk/blog/2017-12-12-standard-format-citation-files).