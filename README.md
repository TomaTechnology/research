# research

This repo is used to organize assets and documentation for TomaTech's research publication; hosted at research.toma.tech


## Structure

For authors, the primary directory of concern is `docs`.

Below is the directory structure:

```
.
├── README.md
└── docs
    ├── 00_example
    │   ├── assets
    │   ├── doc00.md
    │   └── doc00.pdf
    ├── 01_a_new_unit_of_account_for_craftsmen
    │   ├── assets
    │   └── doc01.md
    └── 02_the_last_trade
        ├── assets
        └── doc02.md
```


The `docs` folder contains sub-directories named after the title of the paper, prefixed by the issue number.

Each title directory contains :

- an `assets` sub-directory to save relavent images, documents, icons etc
- an md filed named after the issue number and prefixed with `doc`
- a pdf file which will be created only after the entire research is complete and ready for publication


## doc.md

All md files start with a metadata block. 

If you are an author, add your name to the author section.

Refer to `docs/00_example/doc00.md` for an example.


### Process

The research process begins with first laying out a Table of Contents.

This keeps the research bounded.

If you are collaborating with other authors, DO NOT delete any existing work.
Either only add, or create a copy of the document with your updates. For example,
if you wish to make a complete update to `doc00.md`, copy the contents into a 
`doc00_01.md` and add an `update` field to the metadata block describing the update.

Refer to `docs/00_example/doc00_01.md`

