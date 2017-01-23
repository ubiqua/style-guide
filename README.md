# Ubiqua Style Guide

The HTML browsable website is located in the folder _'_site'_. To share with developers just zip that directory.


## Maintaining the documentation

This guidelines use [Jekyll](https://jekyllrb.com) as static site generator.

To install jekyll in your environment:

    $ gem install jekyll

To install required packages:

    $ cd ubiqua-style-guide     # access your ubiqua style guide copy
    $ bundle install

To run the jekyll server

    $ jekyll serve

Finally, open the browser in http://localhost:4000


These guidelines have 3 main documents:

* __ui-specifications.sketch__, which contains the specification of the controls made with [Sketch](https://www.sketchapp.com)

* __ui-specifications.pdf__ an export of the sketch file in PDF.

* __guidelines.md__, a text written in markdown that explains the usage of the controls specified in the _ui-specifications_. As well, it provides several usability guidelines.


Whenever the `.sketch_` file is updated these are the steps required to keep all the docs sync:

1. On Sketch, make an export to pdf `File/Export artboards to PDF` and save it overwriting the __ui-specifications.pdf__ file.
2. On Sketch, make an export of all the slides. Go to the menu `File/Export...` and select `Export all` checkbox. Save the files under the `images`folder of these guidelines.

If a new slice was created or it's name was changed, be sure to modify `guidelines.md`to include a reference to the image.

## Sketch conventions

The following conventions have been used on the sketch file:

* All documentation artboards use the A4 size. The only exceptions are those with screen examples.
* The contents are divided in pages. Page names are in capital letters.
* Slices are exported in `1.5x` and `png` format.
* Slices are in lower case and words are separated with `-`.
* Slices include the name of the page and an slash in their names. Example: a slice on the CONTROLS page `controls/name-of-the-slice`.
* Groups with the css specifications, all have the name `css`.
* Shared styles used as part of the documentation start with `doc.` prefix.
