**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**
**This repository is an example of a future representation of the ACRIS Semantic Model on GitHub. The complete content is exemplary and not intended for further use!**
**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**


![ACRIS](https://github.com/rogalm/ACRIS/blob/main/Images/ACRISLogo.JPG)

# ACI ACRIS Semantic Model (ASM)

The ACRIS Semantic Model contains the data model for airport and aviation specific domains.

## Structure

The tool for modelling the ASM is currently Enterprise Architect from Sparxsystem. <br>
The content on GitHub is generated from the model in Enterprise Architect. <br><br>

The model is represented in some formats.

### Folder 'html'
This folder contains a html export of the package in Enterprise Architect

### Folder 'json'
This folder contains the data structure in json format

### Folder #implementation'
Fliles in this folder can be used for the implementation of the model and interfaces like raml, json, etc.

### Folder 'EA-xmi'
This folder contains a EA XMI export of the package which can be used to import into any instance of Enterprise Architect

### Folder 'xml'
This folder contains an xml export of the package.

## How to contribute

**!!! First proposal to be discussed in the ACRIS WG !!!**

* The modelling is done in Enterprise Architect by some experts (-> ACRIS roles)
* A representation of the model is available on GitHub 
* ACRIS projects, airports or any other party can create an own branch to work with.
* Chages are handled with pull requests

### ACRIS initiatives and projects

tbd

### The branching concept

![ASM Branching Concept](https://github.com/rogalm/ACRIS/blob/main/Images/Branching-Concept.jpg)

| Branch | Description | Permissions |
| ------ | ----------- | ----------- |
| main | The main branch alwas holds the published releases of the ASM. Published releases are tagged with a release number like 'ASM Release 2.1' | ASM Manager |
| EA_Model | The EA_Model branch holds changes which are exported from the EA model. | ASM Manager |
| Pre_Release_x_y | After publishing a new release of the ASM, a new pre release branch with the future ASM version number is generated as base for upcomming changes. | Public |
| Work branches | Like 'MUC' or 'SFO' in the example image are branches for ACRIS projects, Airports or any other company. This branches are used for to make extensions or changes to the model.  | Public |

### ASM Change Process

tbd
