# Python in Heliophysics Community (PyHC) Standards

**Purpose**: In the interest of fostering an open, welcoming, collaborative, and interoperable environment, this document lists a set of standards for the Python in Heliophysics Community. We pledge to hold ourselves to these standards to the best of our ability.

Drafted during the Heliopython Meeting of November 2018
Agreed on 10-Dec-2018 by <br>
Name1, Name2, Name 3

Definitions:
* Use of the word “**must**” means that it is a requirement.
* Use of the word “**should**” means that it is a recommendation.
* **Packages** - A package is a collection of Python modules which provide related functionality.
* **Stable Package** - A package whose functionality and user interface is not planned on changing until the next major release.

## Standards

1. **Packaging**: All code must be organized and provided as part of installable Python packages.
2. **Open Development**: All code must be made available and developed publicly.
3. **Releases**: Projects should strive to have consistent and stable releases. Those releases should be made available through PyPI and Conda. Code that is not yet stable must have a release number that is less than 1.0 (e.g. 0.x). Packages should consider using semantic versioning. 
4. **Operating System Support**: Packages must strive to support all major operating systems (e.g., OS X, Linux, Windows).
5. **License**: Projects must provide a license. Projects should use permissive licenses for open source scientific software (e.g., the BSD 2-clause, BSD 3-clause, or BSD+Patent licenses). Copyleft licenses such as GPL are not recommended and OSI-approved permissive licenses are recommended.
6. **Version control**: All code must use version control. It is strongly recommended that projects make use of a distributed version control system (e.g., git).
7. **Coding Style**: Projects must adopt the basic style recommendations of PEP 8 and static analysis tools should be used to identify deviations from the basic style recommendations (e.g. pylint, flake8, pycodestyle).
8. **Documentation**: All functions, classes, and modules must have documentation strings (docstrings) provided in a standard conventions (e.g. numpydoc). Docstrings must describe the code’s purpose, describe all inputs and outputs, and provide examples. High level documentation must also be provided as guides, tutorials, and developer docs. Documentation must be provided in version control with the code and be made available online in a readable form. 
9. **Testing**: Stable packages must provide unit tests of individual components (e.g. functions, classes) as well as integration tests that test the interaction between components that covers most of the code. Testing coverage should be measured. Automated testing is recommended, in which tests are run before any code is merged. System[link] and acceptance[link] testing are also recommended.
10. **Dependencies**: Projects should import the minimum number of packages necessary. 	Adding new dependencies should be a considered decision.
11. **Python 3**: All packages must be compatible or work towards being compatible with Python 3. Providing ongoing support for Python 2 is not recommended as the end of life for Python 2 is January 1, 2020 (see PEP 373).
12. **Duplication**: Duplication of code and functionality is discouraged. Forking projects into new projects is strongly discouraged.
13. **Collaboration**: Contributions to packages must be encouraged. Packages must provide contribution guidelines and clearly explain when a contribution is not accepted.
14. **Binaries**: Binary files should be added to the package repository only when necessary in order to keep packages as light as possible. Jupyter notebooks can be binary files and should not be committed to the package repository but can be provided in other repositories.
15. **Code of conduct**:  Each project must adopt a code of conduct that is compatible with the Contributor Covenant and make it publicly available.
