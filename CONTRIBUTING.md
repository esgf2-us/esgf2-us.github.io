# Contributor's Guide

Contributions to the content are more than welcome - please see the instructions below to get started.

## How to deploy the site locally

1. Clone the repository (`git clone https://github.com/esgf2-us/esgf2-us.github.io.git`)`
2. Install the require packages (`conda env create -f environment.yml`)
3. Run the website from your command line (`myst start`), see more on the [myst website documentation](https://mystmd.org/guide/quickstart-myst-websites)

## How to change content
All of the content is written as Jupyter Notebooks or markdown files. Once you make changes to files in the repository (ex. `README.md`), you can do the following:
1. Make sure the file is in the table of contents (`_toc.yml`), if it is not, add it to the list of files
2. Render the website locally (see previous steps)
3. Commit your changes to github on your own fork of the project, creating a dedicated feature branch (see [git branches content here for more details](https://foundations.projectpythia.org/foundations/github/git-branches.html))

