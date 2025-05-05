# UI Research to Support Explainable AI in Scientific Data Repositories

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## A compendium of code, data, and author's manuscript accompanying the manuscript:

#### This research project seeks to develop an experimental method to quantify user trust in metadata augmented with AI through user interface (UI) cues. Physical scientific data has long been used as sources for scientific research and breakthroughs in the physical sciences. Repositories such as the System for Earth and Extraterrestrial Sample Registration (SESAR) store metadata describing samples, which allows for researchers to catalog and secure their samples and allows for future users to reuse the samples as data points for research. However, because curation methods vary across disciplines, metadata often contains missing values that can inhibit data reuse. In fields where sample collection can be destructive, such as archaeology, this is paramount as metadata allows for contextualization of samples (Faniel et al., 2013). Previous work has been done that remedies this issue by using LLMs that can classify missing metadata values (Song et al., 2024), however quantifying the level of trust users have in metadata enhanced by AI needs further experimentation to understand the best way to communicate that metadata has been enhanced by AI. 

#### The project will design an experiment to evaluate what information researchers need or want to know about how a metadata record has been enhanced by AI. This experiment should be able to be further adapted into a formal study beyond the extent of the capstone. Different UI cues will be researched and developed into “mock” UIs that will explain how AI is used to augment earth science metadata. Various static UIs will be created with  Figma and presented to subjects, who will share their level of trust in the interface though a modified version of the human machine interaction trust scale developed by Jain et al.

## Overview
This repository is organized as a reproducible research compendium. Future updates to this compendium will include a Dockerfile and Binder Container

## File Organization

    analysis/
    |
    ├── logs/
    │   └── log.md          # log of any progress or relevant information
    |
    ├── figures/            # location of the figures produced for the manuscript
    |
    ├── data/
    |   ├── rawData/        # data obtained from elsewhere
    │   └── derivedData/    # data generated from rawData/ and scripts.*
    |   
    └── supplementaryMaterials/
        ├── supplementaryFigures/     
        |                   # supplementary figures for the main manuscript
        └── supplementaryTables/      
                            # supplementary tables for the main manuscript 
    
    R/Python/etc.           # scripts to run in the following order (also see associated README.md)
        └── script.*        # hypothetical script used to wrangle the raw data, produce figures, analyses, and supplementary materials

        

