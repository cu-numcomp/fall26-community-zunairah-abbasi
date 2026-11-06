# Community Software Analysis Proposal

## Software: SciPy

SciPy is an open source Python library for scientific and numerical computing. It provides tools for tasks such as integration, optimization, interpolation, and linear algebra. Its primary audience includes scientists, engineers, researchers, and students who need numerical methods for their work. For this project, I focus on its interpolation tools, which estimate values between known data points.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | 	https://github.com/scipy/scipy   |
| Main/documentation website | 	https://docs.scipy.org/doc/scipy/   |
| Year project was started | 2001  |
| Number of contributors in the past year | 247 Git authors since November 1, 2025, measured October 31, 2026. |
| Number of contributors in the lifetime of the project | 2,062 Git authors, measured October 31, 2026.  |
| Number of distinct affiliations | >10, based on the author affiliations listed in the 2020 SciPy paper. |
| Where do development discussions take place? | GitHub issues and pull requests, and the SciPy development forum: https://discuss.scientific-python.org/c/contributor/scipy  |
| Typical number of emails/comments per week? | I did not measure this. Discussions take place on GitHub and the SciPy development forum.  |
| Typical number of commits per week? | Approximately 30 commits per week, based on 120 commits during October 3–30, 2026. |
| Typical commit size | Median of 2 files and 22 lines changed (insertions + deletions), based on 20 recent non-merge commits. |
| How does the project accept contributions? | 	GitHub pull requests, reviewed by maintainers. New features are typically discussed on the development forum first.   |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Does the project have an AI contribution policy? | https://scipy.github.io/devdocs/dev/conduct/ai_policy.html |
| Are any legal/licensing steps required to contribute? | Contributions use SciPy’s BSD 3-clause license, and contributors keep their copyright. Any reused code needs a compatible license. |

Sources:

- [SciPy 1.0 paper and affiliations](https://pubmed.ncbi.nlm.nih.gov/32015543/)
- [SciPy licensing guidance](https://scipy.github.io/devdocs/dev/core-dev/index.html#licensing)


### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

I used SciPy version 1.14.1 and ran the tutorial and comparison examples successfully. I also tried running the fast interpolation tests using scipy.interpolate.test(label="fast", extra_argv=["-q"]). After installing pytest and hypothesis, the runner reported that no tests ran. I checked the installation and found that the interpolation test folder was missing. Because of this, I could not verify whether SciPy’s tests pass in this environment.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
