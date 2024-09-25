# Microalgae-ID
Building AI curse project
## Summary
This project focuses on the development of an advanced classification system for microalgae species, as well as the identification of their possible morphologies when exposed to specific stress situations. 
## Background
Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?
This is how you make a list, if you need one:
* This project solves the problem of identifying certain microalgae under a microscope to determine contamination or even if we extract a sample from a WWTP, industrial water or a pond, to know which microalgae species we are dealing with and thus adapt the necessary parameters for its optimal growth.
* My motivation came when I saw the growth of a microalgae in a sample collection container of industrial water and I wanted to identify it without doing an RNA analysis (costly and time-consuming). So I quickly looked for an atlas and a large database of microalgae photos to identify it. But I found that there are only atlases but with very few photos. Therefore, I think that with collaboration we could easily make a convolutional network with the different photos and scientific studies
* The interesting thing is the fact of comparing the identity and the state of your crop with other studies that already exist and being able to maintain a higher productivity.
## How is it used?
This model would not only optimize the cultivation process, being able to adjust various parameters according to the morphology of the plant. If not, we could also identify contamination or some microalgae that grow in the most wastewater samples. In this case, if we isolated this microalgae we would obtain greater productivity and treatment effectiveness. It would be useful for researchers and industrial projects.

## Data sources and AI methods
We need data from all scientific studies and researchers who use microalgae in their projects.

## Challenges
This project would not give a 100% accurate result on the specific microalgae strain. For example, within the Chlorophyceae we have Chlorella and within this we can find Chlorella vulgaris and Chlorella pyrenoisdosa. This model could detect with microscope images if it is a Chlorella and which one it is, but within each one there are many strains that are used for research. Identifying within Chlorella vulgaris which strain we are looking at is quite complicated since we would have to look at the DNA. Even so, knowing only the species we could adapt the culture to its needs.

Regarding ethics and rigor, the scientific community should verify the percentage of success of this model.
## What next?
This project could grow to differentiate cancer cells from human cells or tissue cells since the model would be the same, we would just need different training data and certain more variables.

I would need help to optimize the code and collect the necessary images 
## Acknowledgments

As for the code, we can optimize and customize an open source classifier that someone has already developed
