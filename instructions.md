# Gitbook Basics

Gitbook is a text editor designed to work with Github and the Markdown text format.

There is a group repository hosted on Github called [psu-arts-arch](https://github.com/psu-arts-arch) — all the documents for DART courses are stored there as .md files, which can be easily edited through the Gitbook web interface.

This [overview video](https://www.youtube.com/watch?v=ivIipcMiCuI) by Michael Collins goes over how to create new documents and sync them with Github.

1. Go the the psu-arts-arch repository on Github.
2. Create a new repository and give it a name. Be sure to include a ReadMe file.
3. Go to Gitbook and select the psu-arts-arch group. Make sure you're not in your personal Gitbook folder.
4. Create a new document.
5. From the available formats, scroll down and choose 'Github'
6. Select the repository you wish to sync with \(e.g. dart-203\).

## Using the Gitbook Editor

Creating articles in the Gitbook editor will create new `.md` files that will be stored in the Github repository.

To organize your files:

* Click the 'Files' tab in the left sidebar; this lists all the files stored in your repo. 
* Edit the `SUMMARY.MD` file to reflect your desired file structure. Editing the bulleted list by adding new rows or tabbing in will alter the document list under the 'TOC' tab \(TOC stands for Table of Contents\). 
* If you've created new files this way, you'll have to publish them before they'll show up in Github. Select the document in the editor and click the big blue Publish button. 
* You can also create new documents by selecting 'New Article' in the TOC tab and then right clicking it to edit it's Pointer — pointers connect files to entries in the Table of Contents. You could conceivably organize your actual files in a different manner than your TOC.  

You'll also have to 'Publish' your document before any changes will be reflected in the actual files stored on Github.

## Formatting

Here's [a cheat sheet ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)for formatting text in raw Markdown \(as opposed to the GUI offered in the Gitbook web editor\).

Typically, there will be one H1 heading tag \(indicated with a single \# in the markdown code view\) reserved for the title of the page. All other headings will us organized with H2 or higher tags.

The rich editor is not without bugs, and sometimes you will need a way to fix something in the code view. Access advanced markdown editing by switching to Edit Markdown interface mode.

 ![](/assets/Screen Shot 2017-06-27 at 3.52.45 PM.png)

