# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Adding content process

Each big topic is organized in its specific directory, where a `README.md` file has the structured list of papers.
The main `README.md`, place in the root of this repository, must have the table of content only.

Therefore, to contribute with new papers, please:

1. Find the topic where the paper best fit.
2. Write the structured entry for the record. 
   Currently, each record has its date, name, publication's title and repositories.
   1. Date is the date of publication
   2. Name is a common name used to refer to the record. For instance, the model or the dataset name. Not every paper has the model's name directly in its title. An example is PubMedBERT, which publication is entitled "Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing".
   3. Publication is the publication's title. The title should be a link for the publication.
   4. Repositories contains links for available code, weights, dataset, downloable dataset, or any available content. Currently I have logos for GitHub and for HuggingFace repositories. Any other platform can be added as needed. Please follow the examples if you want to add a new asset.
   > Please note that the path for the github logo is slightly different in the topic's directory. Please, folow examples already available

|   Date    |     Name    | Publication | Repositories |
| :-------: | :---------- | :--------- | :---------: |
| `YYYY/MM` | Known name  |  [Title](link_to_the_paper) | [<img src="assets/github-mark-white.svg" width="20" />](link_to_github_repo) | 
| `YYYY/MM` | Known name  |  [Title](link_to_the_paper) | [🤗](link_to_huggingface) |
| `YYYY/MM` | Known name  |  [Title](link_to_the_paper) | [<img src="assets/github-mark-white.svg" width="20" />](link_to_github_repo) [🤗](link_to_huggingface) |

3. Add the new record in the correct subsection.
4. Open a Pull Request

## Pull Request Process

1. Update the README.md with details of changes to the interface, this includes new environment 
   variables, exposed ports, useful file locations and container parameters.
2. Increase the version numbers in any examples files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
   Given a version = X.Y.Z, please, increment Z. 
   X is reserved for major releases and Y for minor release patches and the maintainers are responsible for incrementing those.
3. You may merge the Pull Request in once you have the sign-off of the maintainers, or if you 
   do not have permission to do that, you may request the maintainer to merge it for you.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at [INSERT EMAIL ADDRESS]. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
