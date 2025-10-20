# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a LEGO model design repository for a business card holder. The project includes model files and build instructions, not traditional software code. The design evolved from version 1 (LeoCAD) to version 2 (Studio).

## File Formats

- **`.ldr`**: LeoCAD model format (version 1, Lime and Yellow)
- **`.io`**: BrickLink Studio model format (version 2)
  - `business_card_holder2.io`: Lime and Yellow version
  - `business_card_holder2_blue.io`: Blue and White version
- **`.pdf`**: Build instructions exported from Studio
- **HTML/PNG**: LeoCAD-generated instructions in `leocad_v1_instructions/`

## Design Tools

- **Version 1**: [LeoCAD](https://www.leocad.org/) - open source CAD application for creating virtual LEGO models
- **Version 2**: [Studio](https://www.bricklink.com/v3/studio/download.page) - BrickLink's LEGO CAD tool
  - Studio can import LDR files from LeoCAD
  - PDF instructions are generated from Studio

## Markdown Compliance

All Markdown files should comply with `markdownlint`. Use `markdownlint-cli2` to check compliance before committing changes.

## Design Philosophy

The design improves on LEGO's official set 850425 by:
- Adding a sloped back (instead of straight) like traditional business card holders
- Optimizing part costs (e.g., replacing expensive Technic 1x12 brick with three cheaper parts)
- Supporting custom color combinations (Lime/Yellow, Blue/White, etc.)

## Repository Structure

- `/img/`: Product photos and badges
- `/leocad_v1_instructions/`: HTML and PNG instruction files from LeoCAD
- Root directory: Model files, PDF instructions, and main documentation

## Contributing

Refer to [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for contributor expectations. File issues for bugs or feature requests not already listed in [TODO.md](TODO.md).
