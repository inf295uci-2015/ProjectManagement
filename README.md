# ProjectManagement
Any project management resources needed to be shared within the Software Comprehension INF295 course

## Project Milestones
- Create GitHub account, shared resources
- Create a Travis account
- Choose a software project, preferably with the following attributes
-- Sufficiently large, so as to *need* some assistance with program comprehension
-- Sufficiently popular, so that anyone cares
-- Has more than a single contributing developer, so that there is some division of expertise within the codebase
-- Has test cases already written
-- Is hosted in GitHub, or that we mirror to GitHub, so that we can use TravisCI
-- Has build scripts, so that building and testing are easier
-- Already has TravisCI integration
- Build and test your software project locally
- Build and test your project within Travis
- Instrument the code, using the per-test-case version of Jacoco, locally
- Instrument the code, using per-test-case Jacoco, on Travis
- Export the coverage information off of the Travis VM onto a machine that we can control and archive (perhaps by commiting back to the mirrored GitHub repository)
- Automate the GitHub mirroring, so that each time that the project developers commit a new change to the official repo, our mirrors also update, which then launches the Travis build-and-test (and coverage)
- Implement a SeeSoft visualization in the browser
- Implement an interface that allows individual test cases (i.e., test-case methods) to be incluced or excluded from the SeeSoft visualization
- Implement a view that allows the full-size source code to be displayed upon mousing-over (or clicking, or some sort of selection method) the SeeSoft view
- Implement the Tarantula metric so that the hue and brightness of each line can be computed after coverage has been gathered
- Display the Tarantula colors on the SeeSoft visualization
-- Perhaps insert some bugs into a branch of the code so that we can evaluate whether the Tarantula metric helps localize the bug
- Time permitting, create other program-comprehension assistance. Such as:
-- Developer recommendations for fixing failed test cases
-- "The Brain"
-- Concept localization / labeling (perhaps on top of The Brain)
-- ... 