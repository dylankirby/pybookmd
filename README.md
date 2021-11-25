# Pybook

Pybook is a simple, minimalistic CLI for generating books from markdown files


## Installation

``pip install pybookmd``

## Running

``pybookmd``

## Prompts

You'll be prompted for the title of the book

## Optional Arguments

By default pybookmd will look for the markdown files of your book in ``./chapters``, and put the output files in ``./release`` you can however override this.

``pybookmd --chapters_dir <path_to_directory_with_markdown_files> --release_dir <desired_output_directory>``

## Supported Output Formats

Current supported outputed formats

- PDF

Future development may include

- EPUB
- MOBI