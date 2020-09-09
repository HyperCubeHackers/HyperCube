# HyperCube

## Link Index

  - [Design Docs][designdocs]
  - [Design Ethos][designethos]

[designdocs]: https://drive.google.com/drive/folders/1R9QXF1T4d7qh88SowBKQIfeis_v7CTMd?usp=sharing
[designethos]: designethos.md

## What is HyperCube?

HyperCube is a homebrew computer system designed with hackers in mind.
Everything about the machine is open source, from the CPUs, GPUs, sound modules,
and so on.

## How is it designed?

![HyperCube Module Model](https://github.com/HyperCubeHackers/HyperCube/raw/master/docs/assets/module.png "HyperCube Module Model, exploded view")

Primarily, the system is composed of a backplane with a custom point-to-point
bus based around an FPGA. The cores are fully open source and hackable, and the
backplane is fully modular, allowing for CPUs to be plugged in arbitrarily.

The system is expandable with card-edge expansion boards called "modules", and
supports up to eight installed at once.

In terms of hardware design and part choices, we're planning on making the
modules as hackable as possible (ie: perfboard-like with TQFP-144 parts), while
the backplane will be more modern (BGA, QFN, etc.) due to the complexity of the
bus. This means that hackers can make whatever modules they like relatively
easily at home. This isn't to say we're excluding folks, of course, since
everything will be opened for all to see. It's just that the backplane will
require more advanced engineering skill and monetary cost.

## Where are the design docs?

Currently the design documents are stored in [Google Drive, here][designdocs].
These designs are editable only by the development team at the moment, but
viewable by anyone with the link. As the team finalizes each design, we'll
convert them to ODT or Markdown format and put them in source control.

## What tools are you using?

At the moment, the answer is anything we can get our hands on!

  * OnShape
  * Altium Designer
  * Emacs
  * Google Docs
  * *Lots* of whiteboards
  * Brains!

## How do I contribute?

Right now we want to keep the team small so we can focus -- HyperCube is a big
project, and there's lots to do. The hardware is still nacient, and until we at
least make it to the [EVT stage][evt] for the backplane, there probably won't be
much to do with source code. For now, this repository will hold our prototypes.

[evt]: https://en.wikipedia.org/wiki/Engineering_validation_test "Engineering validation test"
