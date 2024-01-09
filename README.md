# A template for a new latex project.
Includes scientific packages.
Includes a cheat sheet for many of the most common features.
Has a dedicated file structure for
- inner files
- source code
- data input / measurement folder
- data output and image folders for file inclusion
- documentation, manuals and other resources

## Using this template
To use this template for your own projects, either fork this repository into your own workspace or download/clone the repo directly on your machine.

The main latex file is located at root.

An example is given in the [example branch](https://github.com/dfb159/latex_vorlage/tree/example).

## Using with VS Code
If you have a latex distribution (e.g. [tex-live](https://www.tug.org/texlive/)) and the LaTeX Workshop extension installed, you can just open the freshly cloned repo and start writing.

You can enable the preview mode and activate auto compile on file change.
This way you will see all your changes instantly.

## Using with external data analysis tools
If you don't want to paste your data manually into the latex files every time you run your analysis tools, use the ```\include{path}``` command to dynamically bind files, which were produced by your analysis tools.
Keep in mind, that the file path is a relative path originating from the root latex file.

If you are using python, you may want to have a look at my [pyGuide](https://github.com/dfb159/pyGuide).
For analysis task you can use [smpl by APN-Pucky](https://github.com/APN-Pucky/smpl/tree/master) or [smplr by me](https://github.com/dfb159/smplr).
They both provide a multitude of very useful analysis helper tools, including uncertainty propagation, fitting, plotting and input/output of data.
