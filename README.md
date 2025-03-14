# Automatic Face Analysis

This repository shall provide a collection about databases and tools for the analysis of faces. 
Please note that this repo is under development. Feel free to reach out for additions, and/or corrections. If you find a link or reference is outdated, I am happy to receive your feedback for corrections. 
Access rights to the databases might change or licenses might run out. 

**Important note:** 
I do not own any of the following databases. For questions about access and details, please contact the respective authors. 


## Datasets
unsorted list coming. Below you find some tables, in an attempt to sort the information. 

- [YouTube Facial Palsy (YFP) Database](https://sites.google.com/view/yfp-database#h.p_DaUvW9mE7B_g) (2018): 32 videos of 21 patients from YouTube, and  a few patients have multiple videos. available upon request
- [Aff-Wild2](https://ibug.doc.ic.ac.uk/resources/aff-wild2/) (2019): The Aff-Wild2 is annotated in a per frame basis for the seven basic expressions (i.e., happiness, surprise, anger, disgust, fear, sadness and the neutral state), twelve action units (AUs 1,2,4,6,7,10,12,15,23,24,25, 26) and valence and arousal. In total Aff-Wild2 consists of 564 videos of around 2.8M frames with 554 subjects (326 of which are male and 228 female). All videos have been annotated in terms of valence and arousal. 546 videos of around 2.6M frames have been annotated in terms of the basic expressions. 541 videos of around 2.6M frames have been annotated in terms of action units. Aff-Wild2 displayes a big diversity in terms of subjects' ages, ethnicities and nationalities; it has also great variations and diversities of environments. Available upon request for academia and industry
- [Depresjon](https://datasets.simula.no/depresjon/) [kaggle](https://www.kaggle.com/datasets/arashnic/the-depression-dataset) (2018): A Motor Activity Database of Depression Episodes in Unipolar and Bipolar Patients:  motor activity recordings of 23 unipolar and bipolar depressed patients and 32 healthy controls. - freely available
- [RAVDESS](https://zenodo.org/record/1188976#.ZCPaFC8Robx) (2018): The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains 7356 files (total size: 24.8 GB). The database contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. - under a Creative Commons Attribution 
- [JAFFE](https://zenodo.org/record/3451524) (1998): 10 Japanese female expressers, 7 Posed Facial Expressions (6 basic facial expressions + 1 neutral), Several images of each expression for each expresser 
213 images total, each image has averaged semantic ratings on 6 facial expressions by 60 Japanese viewers. available upon request for non-commercial scientific research 
- [DASPS database ](https://ieee-dataport.org/open-access/dasps-database) (2021): raw EEG data collected from the 23 participants during anxiety. "We provided a matlab script for the segmentation of each EEG signal into 6 segments corresponding to the 6 situations.".
- [Cardiff Conversation Database (CCDb)](https://ccdb.cs.cf.ac.uk/) (2013): audio-visual natural conversation database with 2D and 3D data. access upon request
- [EMU: Early Mental Health Uncovering](https://github.com/mltlachac/EMU) (2021)
- more datasets: [here](https://emutivo.wpi.edu/index.php/data/)
- "The Turkish Audio-Visual Bipolar Disorder Corpus", Ciftci, Kaya (2018). audio-visual Bipolar Disorder (BD) corpus for the affective computing and psychiatric communities - has become unavailable. Time period of permitted use ran out. (add to list of deprecated databases?)
- 2do: check all AVEC, e.g. [AVEC2013](https://github.com/chkche1/avec2013), [AVEC2019](https://sites.google.com/view/avec2019/home) for availabilty
- 2do: more [face rec databases](https://www.face-rec.org/databases/)
- 2do: [Binghamton Face Databases](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
- 2do: [Wizard of Oz](https://dcapswoz.ict.usc.edu/)
- [promising overview](https://www.mdpi.com/1424-8220/22/4/1524)

<!-- Files have not yet been uploaded: for "Facial Paralysis Dataset" https://ieee-dataport.org/documents/facial-paralysis-dataset#files-->

### Infant Datbases
- [The City Infant Faces Database: A validated set of infant facial expressions](https://pmc.ncbi.nlm.nih.gov/articles/PMC5809537/)  "60 photographs of positive infant faces, 54 photographs of negative infant faces, and 40 photographs of neutral infant faces."
- [Tromsø Infant Faces Database](https://uit.no/project/norbaby/database) contains 119 images of infant facial expressions
- [The Child Affective Facial Expressions Set (CAFE)](https://www.childstudycenter-rutgers.com/the-child-affective-facial-expression-se)
- [A Dataset of Eye Movements for the Children with Autism Spectrum Disorder](https://zenodo.org/records/2647418)

### Facial Expression Databases
<!-- Usage of the table
    Name: name of the dataset
    Year: year of publication
    Description: a short description of the dataset
    Tags: tags of the dataset e.g "audio" : :sound: , "video" : :movie_camera: , "image" : :camera:
    link: link to the dataset
    Licence: In what context is the dataset allowed to be used e.g "research only"

 -->

|Name|Description|Number of Subjects|Number of images/videos|Facial Expressions|Modalities|Licence|
|:-|:-|:-:|:-:|:-|:-|:-:|
| [Aff-Wild2](https://ibug.doc.ic.ac.uk/resources/aff-wild2/) | multimodal dataset for affect recognition and analysis. videos of people displaying a range of emotions and facial expressions. 2 parts: (1) AffWild2-Train - 1200 videos of various emotions and facial expressions, and (2) AffWild2-Test - ca. 200 videos for evaluation. |10|213 static images|neutral, happiness, sadness, surprise, fear, disgust, anger + valence-arousal + action units 1,2,4,6,12,15,20,25|:camera: :movie_camera: :sound: | non-commercial |
|[JAFFE](https://www.kasrl.org/jaffe.html)| The Japanese Female Facial Expression Dataset (JAFFE) 10 japanese female participants, each expressing 7 basic emotions (anger, disgust, fear, happiness, sadness, surprise, and neutral) 3 times. 213 images.|458|2.800.000 manually annotated|neutral, sadness, surprise, happiness, fear, anger, and disgust|:camera:|non-commercial|
|[RAVDESS](https://zenodo.org/record/1188976#.ZCPaFC8Robx)|Actors either talking or sining two different sentences in a neutral, calm, happy, sad, angry, fearful, disgust, or suprised tone of voice.|24|2452 videos|neutral, calm, happy, sad, angry, fearful, disgust, suprised|:movie_camera: :sound:|non-commercial|




<p align="right">[<a href="#readme-top">back to top</a>]</p>

### Mental Health Databases
<!-- table content
    Name: name of the dataset
    Year: year of publication
    Description: a short description of the dataset
    Tags: tags of the dataset e.g "audio" : :sound: , "video" : :movie_camera: , "image" : :camera:
    link: link to the dataset
    Licence: In what context is the dataset allowed to be used e.g "research only"

 -->

|Name|Year|Description|Number of Subjects|Mental Disorder|Labels|Modalities|Availability|
|:-|:-|:-|:-:|:-:|:-|:-|:-:|
|[Depresjon](https://datasets.simula.no/depresjon)|2018| A Motor Activity Database of Depression Episodes in Unipolar and Bipolar Patients| 55 |depression, unipolar/bipolar|MADRS|motor activity recordings|free to download|
| AVEC2014 |2014| The Audio/Visual Emotion Challenge and Workshop | xx | depression | PHQ | | upon request|
|[AVEC2013](https://github.com/chkche1/avec2013)|2013| The Audio/Visual Emotion Challenge and Workshop | 292 | depression |BDI, valence, arousal|audio features|free to download|
|-|

## Related Human Motion Databases
2do: add to another repo
- [AIFit: Automatic 3D Human-Interpretable Feedback Models for Fitness Training](https://fit3d.imar.ro/)
- [Human3.6M](http://vision.imar.ro/human3.6m/description.php) 


## Tools
### Facial Action Units and more
- [OpenFace](https://openface-api.readthedocs.io/en/latest/)
- [Python Facial Expression Analysis Toolbox (Py-Feat)](https://py-feat.org/pages/intro.html)
- PyAFAR: Python-based Automated Facial Action Recognition library for use in Infants and Adults: [website](https://pyafar.org/), [github](https://github.com/AffectAnalysisGroup/PyAFAR)

### Facial Landmarks only
- [dlib](http://dlib.net/)
- [Mediapipe](https://developers.google.com/mediapipe/)

## Models
Publicly available models.
- [Candide-3](candide3.md): 3D wireframe model: 113 3D vertices connected with triangles, parameters for changing of the shape and expression of the 3D face
- [Basel Face Model](https://faces.dmi.unibas.ch/bfm/) - 3D Morphable Face Model (Shape and Texture)

## Audio
[speech data with depression labels](https://github.com/speechandlanguageprocessing/ICASSP2022-Depression)

## Related Project Page
[Affective Computing](https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange)

## Contact
[Stella Grasshof](https://pure.itu.dk/en/persons/stella-grasshof) - IT University of Copenhagen

<p align="right">[<a href="#readme-top">back to top</a>]</p>
