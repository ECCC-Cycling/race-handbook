# ECCC Race Handbook

A comprehensive guide of collegiate cycling races for event organizers, volunteers, athletes, and contracted event service providers.

Some of the guide's contents, such as handouts for marshals, can also be compiled into separate documents.

## Building

### Locally

There are many ways to compile LaTeX documents, but the following steps are one way to setup your local machine and compile this document.

1. Install MiKTeX
1. Clone this repository, and open with Visual Studio Code
1. Install Kaobook by either of the following options:
   1. Copy the following files into the root of this repository:
      - `kao.sty`
      - `kaobiblio.sty`
      - `kaobook.cls`
      - `kaorefs.sty`
      - `kaotheorems.sty`
   1. Setup kaobook globally
      1. Create a directory, e.g. `C:\Users\<Username>\AppData\Local\localtexmf`
      1. Inside `localtexmf`, create `tex/latex/`
      1. Clone the `kaobook` repository inside the `latex` directory
