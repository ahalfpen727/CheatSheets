
## Cheat Sheets for R, Python, Linux Command Line, System Administration
Useful cheatsheets I have picked up along the way. Mostly R data analysis package resources

# RStudio Cheatsheets

<img src="pngs/rstudio-ide.png" width=364 height=288 align="right"/>

The cheat sheets make it easy to learn about and use some of our favorite packages. They are published in their respective PDF versions here: https://www.rstudio.com/resources/cheatsheets/, some are also available in the RStudio IDE under Help-Cheatsheets.

This repository contains the source Apple Keynote files or the current, archived and translated versions.

The cheat sheets use the creative commons copyright. Please see the LICENSE document for more details.

## Translations

If you wish to contribute to this effort by translating a cheat sheet, please feel free to use the source Keynote file. To submit a translation, please use a Pull Request via GitHub or email it to us at [info@rstudio.com](mailto:info@rstudio.com) with the subject "Translated Cheatsheet".

## Tips for making a new cheat sheet

Keep these tips in mind when creating a new cheat sheet:

1. RStudio cheat sheets are hosted at https://github.com/rstudio/cheatsheets. You can submit new cheat sheets to the repository with a pull request.

1. The files `keynotes/0-template.key` and `powerpoints/0-template.ppt` are official templates that contain some helpful tips.

    > Tip. You may find it easier to create a new cheat sheet by duplicating the most recent Keynote / Powerpoint cheat sheet.

1. The cheat sheets are not meant to be text documents. Ideally, they are scannable visual aids that use layout and visual mnemonics to help people zoom into the functions they need. As an analogy, think of a cheat sheet as more like a well organized computer menu bar that leads you to a command than a manual that documents each command.

1. The cheat sheets use a cohesive, black and white printer friendly theme (which is what you see in the sheets), so please stay close to the appearance of the existing sheets.

1. It's already baked into every cheat sheet and the template, but you should include a [Creative Commons](https://creativecommons.org/) Copyright on each side of the sheet to make them easy to repurpose.

1. Budget more time than you expect to make the sheets. So far, I've found this process to be the least time consuming:

    * Use the package web page and any vignettes to identify which functions to include (I try to include anything that doesn't seem trivial.)

    * Organize the functions into meaningful, self-explanatory groups.

    * Think about how to visualize the purpose of each function.

    * Think about what key mental models, definitions, or explanations the cheat sheet should contain in addition to the functions.

    * Sketch out several possible layouts for the sheet. Take care to put the more basic and/or pre-requisite content above and to the left of other content. Try to keep related content on the same side of the page.

    * Type out all of the explanations and function definitions. Lay them out. Verify that everything fits. White space is very important. Use it to make the sheet scannable, even if it means smaller text.

    * Making the visuals is the most time consuming part, so I usually save them for last.

    * Tweak until happy. 

1. Pay attention to the details!

> Final tip: Edit the text to be very concise - rely on diagrams where possible.

![CSCounterBadge](https://img.shields.io/badge/Cheat_sheets_available-61-orange.svg)
![LicenseBadge](https://img.shields.io/badge/License-C_C-blue.svg)
[![PushAndPullRequestIntegrityCheck](https://travis-ci.org/OWASP/CheatSheetSeries.svg?branch=master)](https://travis-ci.org/OWASP/CheatSheetSeries)
[![OfflineWebsiteBuild](https://circleci.com/gh/OWASP/CheatSheetSeries/tree/master.svg?style=svg)](https://circleci.com/gh/OWASP/CheatSheetSeries/tree/master)

![OWASPHeader](assets/Preface_Cheatsheet_Header.png)

![ProjectLogoOfficial](assets/Preface_Cheatsheet_Logo.png)

# Welcome to OWASP Cheat Sheet Series V2

This repository contains all the cheat sheets of the project and represent the V2 of the [OWASP Cheat Sheet Series](https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series) project.

# Table of Contents

- [Cheat Sheets index](#cheat-sheets-index)
- [Special thanks](#special-thanks)
- [Editor & validation policy](#editor--validation-policy)
- [Conversion rules](#conversion-rules)
- [How to setup my contributor environment?](#how-to-setup-my-contributor-environment)
- [How to contribute?](#how-to-contribute)
- [Offline website](#offline-website)
- [Project leaders](#project-leaders)
- [Core technical review team](#core-technical-review-team)
- [PR usage for core commiters](#pr-usage-for-core-commiters)
- [Project logo](#project-logo)
- [Folders](#folders)
- [License](#license)
- [Code of conduct](CODE_OF_CONDUCT.md)

# Cheat Sheets index

The following indexes are provided:
* This [index](Index.md) reference all released cheat sheets sorted alphabetically.
    * This index is automatically generated by this [script](scripts/Update_CheatSheets_Index.py).
* This [index](IndexASVS.md) reference all released cheat sheets using the [OWASP ASVS](https://www.owasp.org/index.php/Category:OWASP_Application_Security_Verification_Standard_Project) project as reading source.
    * This index is manually managed in order to allow contribution along custom content.
* This [index](IndexProactiveControls.md) reference all released cheat sheets using the [OWASP Proactive Controls](https://www.owasp.org/index.php/OWASP_Proactive_Controls) project as reading source.
    * This index is manually managed in order to allow contribution along custom content.

You can also search into this repository using a keywords via this URL:

```text
https://github.com/OWASP/CheatSheetSeries/search?q=[KEYWORDS]
```

Example:

```text
https://github.com/OWASP/CheatSheetSeries/search?q=csrf
```

More information about the GitHub search feature can be found [here](https://help.github.com/en/articles/about-searching-on-github).

Below are the steps to properly submit a PR:
1. Clone the project.
2. Move on to the `master` branch: 
    > `git checkout master`
3. Ensure that you have the latest files:
    > `git pull`
4. Create a branch named `CSS-[ID]` where **[ID]** is the number of the linked issue opened prior to the PR to follow the contribution process:
    > `git checkout -b CSS-[ID]`
5. Switch to this new branch (normally it's already the case):
    > `git checkout CSS-[ID]`
6. Do the expected work.
7. Push the new branch:
    > `git push origin CSS-[ID]`   
8. When the work is ready for the review, create a pull request by visiting this link:
    > `https://github.com/OWASP/CheatSheetSeries/pull/new/CSS-[ID]`
9. Implement the modifications requested by the reviewers. Once the reviewers approve the PR, it is then merged to the `master` branch.
10. Once merged, delete the branch using this [GitHub feature](https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository#deleting-a-branch).

See project current [branches](https://github.com/OWASP/CheatSheetSeries/branches).

# Project logo

Project's official logo files are hosted [here](https://github.com/OWASP/owasp-swag/tree/master/projects/cheat-sheet-series).

# Folders

**cheatsheets_excluded**:
* Contains the cheat sheets markdown files converted with PANDOC and for which a discussion must be made in order to decide if we include them into the V2 of the project due to the content has not been updated since a long time or is not relevant anymore. See this [discussion](https://github.com/OWASP/CheatSheetSeries/issues/13). 

**cheatsheets**: 
* Contains the final cheat sheets files. 
* Any `.md` file present into this folder is considered released.

**assets**: 
* Contains the assets used by the cheat sheets (images, pdf, zip...).
    * Naming convention is `[CHEAT_CHEET_MARKDOWN_FILE_NAME]_[IDENTIFIER].[EXTENSION]`
    * Use `PNG` format for the images.

**scripts**:
* Contains all the utility scripts used to operate the project (markdown linter audit, dead link identification...).    

**templates**:
* Contains templates used for different kinds of files (cheatsheet...).

**.github**:
* Contains materials used to configure different behaviors of GitHub.

**.circleci** / **.travis.yml** (file):
* Contains the definition of the integration jobs used to control the integrity and consistency of the whole project:
    * **[TravisCI](https://travis-ci.org/OWASP/CheatSheetSeries)** is used to perform compliance check actions at each Push/Pull Request. **It must be/stay the fastest possible** (currently inferior to 2 minutes) in order to provide a rapid compliance feedback about the Push/Pull Request.
    * **[CircleCI](https://circleci.com/gh/OWASP/CheatSheetSeries)** is used to perform operations taking *longer time* like build, publish and deploy actions.

# Offline website

Unfortunately, a PDF file generation is not possible because the content is cut in some cheat sheets like for example the abuse case one.

However, to propose the possibility the consult, in a full offline mode, the collection of all cheat sheets, a script to generate a offline site using [GitBook](https://toolchain.gitbook.com/) has been created. The script is [here](scripts/Generate_Site.sh).

* **book.json**: Gitbook configuration file.
* **Preface.md**: Project preface description applied on the generated site.

## Automated build

This [link](https://owasp.github.io/CheatSheetSeries/bundle.zip) allow you to download a build (zip archive) of the offline website.

## Manual build

Use the commands below to generate the site:

```bash
# Your python version must be >= 3.5
$ python --version
Python 3.5.3
# Dependencies:
#  sudo apt install -y nodejs
#  sudo npm install gitbook-cli -g
$ cd scripts
$ bash Generate_Site.sh
Generate a offline portable website with all the cheat sheets...
Step 1/5: Init work folder.
Step 2/5: Generate the summary markdown page.
Index updated.
Summary markdown page generated.
Step 3/5: Create the expected GitBook folder structure.
Step 4/5: Generate the site.
info: found 45 pages
info: found 86 asset files
info: >> generation finished with success in 14.2s !
Step 5/5: Cleanup.
Generation finished to the folder: ../generated/site
$ cd ../generated/site/
$ ls -l
drwxr-xr-x 1 Feb  3 11:05 assets
drwxr-xr-x 1 Feb  3 11:05 cheatsheets
drwxr-xr-x 1 Feb  3 11:05 gitbook
-rw-r--r-- 1 Feb  3 11:05 index.html
-rw-r--r-- 1 Feb  3 11:05 search_index.json
```

# Conversion rules

* Use the markdown syntax described in this [guide](https://guides.github.com/features/mastering-markdown/).
* Use this [sheet](https://gist.github.com/molomby/9bc092e4a125f529ae362de7e46e8176) for Superscript and Subscript characters.
* Use this [sheet](https://meta.askubuntu.com/a/7383) for Arrows (left, right, top, down) characters.
* Store all assets in the **assets** folder and use the following syntax:
    * `![ALTERNATE_NAME](../assets/ASSET_NAME.png)` for the insertion of an image. Use `PNG` format for the images (this [software](https://www.gimp.org/downloads/) can be used to handle format conversion).
    * `[ALTERNATE_NAME](../assets/ASSET_NAME.EXT)` for the insertion of other kinds of media (pdf, zip...).
* Use ATX style (`#` syntax) for section head. 
* Use `**bold**` syntax for **bold** text.
* Use `*italic*` syntax for *italic* text.
* Use `TAB` for nested lists and not spaces.
* Use [code fencing syntax along syntax highlighting](https://help.github.com/articles/creating-and-highlighting-code-blocks/) for code snippet (prevent when possible horizontal scrollbar).
* If you use `{{` or `}}` pattern in code fencing then add a space between the both curly braces (ex: `{ {`) otherwise it break GitBook generation process.
* Same remark about the cheat sheet file name, only the following syntax is allowed: `[a-zA-Z_]+`.
* No HTML code is allowed, only markdown syntax is allowed!
* Use this [site](https://www.tablesgenerator.com/markdown_tables) for generation of tables.
* Use a single new line between a section head and the beginning of its content.

# Editor & validation policy

[Visual Studio Code](https://code.visualstudio.com/) is used for the work on the markdown files. It is also used for the work on the scripts.

The file **Project.code-workspace** is the workspace file in order to open the project in VSCode.

The following [plugin](https://github.com/DavidAnson/vscode-markdownlint) is used to validate the markdown content.

The file **.markdownlint.json** define the central validation policy applied at VSCode (IDE) and TravisCI (CI) levels.

Details about rules is [here](https://github.com/DavidAnson/markdownlint/blob/master/doc/Rules.md).

The file **.markdownlinkcheck.json** define the configuration used to validate using this [tool](https://github.com/tcort/markdown-link-check), at TravisCI level, all web and relatives links used in cheat sheets.

# How to setup my contributor environment?

See [here](CONTRIBUTING.md#how-to-setup-my-contributor-environment).

# How to contribute?

See [here](CONTRIBUTING.md#how-to-contribute).

# Special thanks

A special thanks you to the following peoples for the help provided during the migration:

- [ThunderSon](https://github.com/ThunderSon): Deeply help about updating the OWASP wiki links for all the migrated cheat sheets.
- [mackowski](https://github.com/mackowski): Deeply help about updating the OWASP wiki links for all the migrated cheat sheets.

