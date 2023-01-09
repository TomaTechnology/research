# research

This repo is used to organize assets and documentation for TomaTech's research publication; hosted at research.toma.tech


## Structure

For authors, the primary directory of concern is `docs`.

Given below is the directory structure:

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

Add notes in each section to help other authors know what is required. 

Authors can then asynchronously complete sections and do the research required for each.
