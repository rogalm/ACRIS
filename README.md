**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**<br>
**This repository is an example of a future representation of the ACRIS Semantic Model on GitHub. The complete content is exemplary and not intended for further use!**<br>
**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**<br><br>


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
| main | The ASM releases are published on the main branch. These are tagged with a tag in the form 'Release x.y'. | ACRIS Data Standards Manager |
| EA_Model | The core of the ASM is stored in a separate database as an Enterprise Architect model and is edited with the Enterprise Architect tool from Sparxsystems. Changes to this core in EA are pushed to the EA_Model branch. | ACRIS Data Standards Manager |
| Pre_Release_x_y | After a new ASM release has been published on the main branch, a new pre-release branch is created with the future ASM version number as the basis for future changes. All proposed and accepted changes (via pull request) are available in this branch until a new release is published. | Public |
| Work branches | Anyone who wants to suggest changes or enhancements to ASM can create their own branch from the Pre_Release branch - as shown in the image above for the 'MUC', 'SFO' or 'ACRIS Project' branches. The changes are merged to the Pre_Release branch via merge request.  | Public |

### ASM Change Process

tbd
