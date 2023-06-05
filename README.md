# Introduction

This repo contains a starter for using 'Diagrams as Code' in your project, using plantuml, C4, azure icons. 

Read the article here: https://andysprague.com/2023/01/11/diagrams-as-code-c4-diagrams-with-azure-icons/

## Build/deploy

TODO: CI/CD to azure pipelines.

## Updating diagrams with VSCode

### Prerequisite

Install extension 'plantuml' and leave all default settings. Test correct installation by opening testDot.wsd and previewing with Alt + D. Should see preview with PlantUML version, and message "Installion seems OK"

### To update diagram

- Open the relevant .wsd file
- Preview with Alt + D (or, right-click -> Preview Current Diagram)
- Once done, right click - > Export Current Diagram, choose png format
- View rendered diagram in 'out' folder

### To generate custom sprites

See <https://plantuml.com/sprite> e.g.
- java -jar plantuml.jar -encodesprite 16z prius.svg   

If plantuml.jar is not on your PATH, look for it in a folder 

java -jar "C:\Program Files\PlantUML\plantuml.jar" -encodesprite 16z prius.svg   

## Contact

- andy.sprague44@gmail.com

## License

MIT
