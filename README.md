[![](https://img.shields.io/badge/Open%20In-RStudio%20Cloud-green)](https://rstudio.cloud/content/4771757) *Try without installing anything. Make sure to click the Make a Copy button or you will lose all your changes.*
 
# Welcome to the NWFSC Conservation Biology- Molecular Genetics Landing Page

This is a current work in progress, intended to link out repositories for active and finsihed projects among our group as well as resources for github, coding, and data analysis. Stay tuned for more updates!

To view the front facing webpage, [click here](https://noaa-nwfsc.github.io/CB_Genetics_Landing_Page/)


## Customize

* Edit the qmd or md files in the `content` folder. qmd files can include code (R, Python, Julia) and lots of Quarto markdown bells and whistles (like call-outs, cross-references, auto-citations and much more).
* Add the files to `_quarto.yml` to add pages to the website

## Website Template

* This webpage was built from the [NOAA quarto simple](https://github.com/nmfs-opensci/NOAA-quarto-simple) template created by NMFS Open Science.


## Troubleshooting builds

The most common trouble users run into is that the book is not rendering. Check the following:

* The `gh-pages` branch does not exist. If you forgot to check the check box to include all the branches when you created the repo from the template then it won't exist. The Action will fail if the gh-pages branch does not already exist. You can create the branch and then push a change to main to trigger the Action to run again.
* The GitHub Pages has not been set. You need to go to Pages under settings, and set Pages to build from the `gh-pages` branch.
* You did not allow GitHub Actions to run and/or did not give read/write permission. Go to Settings > Actions > General, and make sure Actions are allowed (top section) and they have read/write permission (bottom section).
* You did not push a change to the main branch. The Action is triggered by a push to main, so try making an edit to README.md and pushing that change.

<hr>

### Disclaimer

This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project content is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.

### License

This content was created by U.S. Government employees as part of their official duties. This content is not subject to copyright in the United States (17 U.S.C. §105) and is in the public domain within the United States of America. Additionally, copyright is waived worldwide through the CC0 1.0 Universal public domain dedication.

<hr>
