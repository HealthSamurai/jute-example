# JUTE Examples

This repository contains example HL7 v2 to FHIR Bundle mapping written
in [JUTE language](https://github.com/HealthSamurai/jute.js).

Also there is
[FHIR Mapping Language tutorial](http://build.fhir.org/mapping-tutorial.html)
translated to JUTE.

Both examples are executable, so you can alter
mapping or source data and see how it affects result.

## HL7 v2 to FHIR Bundle

Mapping file: `adt.yml`

Source message: `adt.hl7`

Executable script: `jute-hl7.js`

Result: `hl7-result.json`

## Mapping tutorial

Both mappings and source data are in same file: `tutorial.yml`

Executable script: `tutorial.js`

Result: `tutorial-result.txt`

## How to make scripts work

- install recent version of node.js (at least 6.x) for your OS
- clone this repository
- init repository submodules with `git submodule update --init`
- install dependencies with `npm install`
- invoke scripts like `node ./jute-hl7.js` or `node ./tutorial.js`

## Comments, questions?

Feel free to write any comments, suggestions or questions to Mike
Lapshin: mlapshin@health-samurai.io
