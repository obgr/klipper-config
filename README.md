
# README
This repository contains my klipper configurations for my 3d printers.

## Why?
I did not have many references for my configuration, so i decided to upload my own configuration if someone else would like to look at it.

## Knowledge base
Odd findings, things that needs to be written down but i don't know where.
I might move this to another file or some suitable wiki somewhere.

### Klipper, Printer wont extrude, but retraction works
This was the symptom of an issue I encountered when helping a friend configure klipper for the first time.
I bevile the issue was that the configuration file (printer.cfg) included both TABs and spaces. No indication of a configuration issue was reported by klipper. The configuration segment that caused the issue  even seemed to work.
