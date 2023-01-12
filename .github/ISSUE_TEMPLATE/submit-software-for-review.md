---
name: Submit Software for Review
about: Use to submit your Python package for pyOpenSci peer review
title: ''
labels: 1/editor-checks, New Submission!
assignees: ''

---

Submitting Author: Name (@github_handle)
All current maintainers: (@github_handle1, @github_handle2)
Package Name: Package name here
One-Line Description of Package: Description here 
Repository Link:  
Version submitted:   
Editor: TBD  
Reviewer 1: TBD  
Reviewer 2: TBD  
Archive: TBD  
Version accepted: TBD 
Date accepted (month/day/year): TBD

---

## Description

- Include a brief paragraph describing what your package does:

## Scope 
- Please indicate which [category or categories][PackageCategories] this package falls under:
	- [ ] Data retrieval
	- [ ] Data extraction
	- [ ] Data munging
	- [ ] Data deposition
	- [ ] Reproducibility
	- [ ] Geospatial
	- [ ] Education
	- [ ] Data visualization*

> *Please fill out a pre-submission inquiry before submitting a data visualization package. For more info, see [notes on categories][NotesOnCategories] of our guidebook.*


- **For all submissions**, explain how the and why the package falls under the categories you indicated above. In your explanation, please address the following points (briefly, 1-2 sentences for each):  

  - Who is the target audience and what are scientific applications of this package?  

  - Are there other Python packages that accomplish the same thing? If so, how does yours differ?

  - If you made a pre-submission enquiry, please paste the link to the corresponding issue, forum post, or other discussion, or `@tag` the editor you contacted:

## Technical checks

For details about the pyOpenSci packaging requirements, see our [packaging guide][PackagingGuide]. Confirm each of the following by checking the box.  This package:

- [ ] does not violate the Terms of Service of any service it interacts with. 
- [ ] has an [OSI approved license][OsiApprovedLicense].
- [ ] contains a README with instructions for installing the development version. 
- [ ] includes documentation with examples for all functions.
- [ ] contains a vignette with examples of its essential functions and uses.
- [ ] has a test suite.
- [ ] has continuous integration, such as Travis CI, AppVeyor, CircleCI, and/or others.

## Publication options

- [ ] Do you wish to automatically submit to the [Journal of Open Source Software][JournalOfOpenSourceSoftware]? If so:

<details>
 <summary>JOSS Checks</summary>  

- [ ] The package has an **obvious research application** according to JOSS's definition in their [submission requirements][JossSubmissionRequirements]. Be aware that completing the pyOpenSci review process **does not** guarantee acceptance to JOSS. Be sure to read their submission requirements (linked above) if you are interested in submitting to JOSS.
- [ ] The package is not a "minor utility" as defined by JOSS's [submission requirements][JossSubmissionRequirements]: "Minor ‘utility’ packages, including ‘thin’ API clients, are not acceptable." pyOpenSci welcomes these packages under "Data Retrieval", but JOSS has slightly different criteria.
- [ ] The package contains a `paper.md` matching [JOSS's requirements][JossPaperRequirements] with a high-level description in the package root or in `inst/`.
- [ ] The package is deposited in a long-term repository with the DOI: 

*Note: Do not submit your package separately to JOSS*
  
</details>

## Are you OK with Reviewers Submitting Issues and/or pull requests to your Repo Directly?
This option will allow reviewers to open smaller issues that can then be linked to PR's rather than submitting a more dense text based review. It will also allow you to demonstrate addressing the issue via PR links.

- [x] Yes I am OK with reviewers submitting requested changes as issues to my repo. Reviewers will then link to the issues in their submitted review.

## Code of conduct

- [ ] I agree to abide by [pyOpenSci's Code of Conduct][PyOpenSciCodeOfConduct] during the review process and in maintaining my package should it be accepted.

## Please fill out our survey
- [ ] [Last but not least please fill out our pre-review survey](https://forms.gle/F9mou7S3jhe8DMJ16). This helps us track
submission and improve our peer review process. We will also ask our reviewers 
and editors to fill this out.

**P.S.** *Have feedback/comments about our review process? Leave a comment [here][Comments]

## Editor and Review Templates

The [editor template can be found here][Editor Template].

The [review template can be found here][Review Template].

[PackagingGuide]: https://www.pyopensci.org/contributing-guide/authoring/index.html#packaging-guide

[PackageCategories]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/aims-and-scope.html?highlight=data#package-categories

[NotesOnCategories]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/aims-and-scope.html?highlight=data#notes-on-categories


[JournalOfOpenSourceSoftware]: http://joss.theoj.org/

[JossSubmissionRequirements]: https://joss.readthedocs.io/en/latest/submitting.html#submission-requirements

[JossPaperRequirements]: https://joss.readthedocs.io/en/latest/submitting.html#what-should-my-paper-contain

[PyOpenSciCodeOfConduct]: https://www.pyopensci.org/contributing-guide/open-source-software-peer-review/code-of-conduct.html?highlight=code%20conduct

[OsiApprovedLicense]: https://opensource.org/licenses

[Editor Template]: https://www.pyopensci.org/peer-review-guide/software-peer-review-guide/editors-guide.html#respond-to-the-submitter-in-the-github-issue

[Review Template]: https://www.pyopensci.org/peer-review-guide/software-peer-review-guide/reviewer-guide.html#peer-review-template

[Comments]: https://github.com/pyOpenSci/governance/issues/8
