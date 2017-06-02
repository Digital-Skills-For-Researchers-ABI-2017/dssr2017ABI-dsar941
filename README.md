## Semantic Annotation and Discovery with CellML and PMR

In this project we will develop a web-based epithelial transport discovery, exploration and assembly tool. By using this tool, users would be able to discover computational physiology models in order to assemble and create an epithelial model.

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

This project would be useful to novice modellers in order to create epithelial models of interest. Some of the features have benn presented below:
* Model discovery - users will search models of interest and the tool will discover and explore those models from the biological annotation of the CellML models from the Physiome Model Repository (PMR) with some useful information such as species, gene, protein names. This helps users to explore and choose models from a wide range of options. 
* Load models - selected models from the discovery step have been loaded here. This includes a visualization feature in order to graphically compare between cellml models. In addition, users would be able to view annotated content of the models such as abstract of the paper, author names, location of the model from multiple reference ontologies.
* Epithelial Platform - this final step will visualize the selected models and will semantically place them in appropriate membranes and compartments. For example, if a user loads a model annotated with J_NHE3_Na vaiable as "flux of sodium from luminal to cytosol through apical membrane", then that variable will be placed on the apical membrane with an arrow direction from the allocated lumen to cytosol space. In addition, users would be able to drag and drop models across different membranes.

Long term goal of this project is to find diseases from the discovered models by linking Bioinformatics using Semantic Web Technologies.

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Clone the project and open the index.html into your browser. Or you could copy and paste the index.html page URI into rawgit.com, which will provide you a web URI.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

- Dewan Sarwar
- David Nickerson (Advisor)
- Tommy Yu (Advisor)

## License

MIT license!
