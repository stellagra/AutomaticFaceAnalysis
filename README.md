# Automatic Face Analysis

This repository shall provide a collection about databases and tools for the analysis of faces. 
The intention is to gather datasets which are available. However, dataset which are not available might be added since those can be helpful as a source of related work. 
Please note that this repo is under development. Feel free to reach out for additions, and/or corrections. If you find a link or reference is outdated, I am happy to receive your feedback for corrections. 

Notes: 
- I neither claim completeness nor correctness. No guarantees. 
- Access rights to the databases might change or licenses might run out. 
- I do not own any of the following databases. For questions about access and details, please contact the respective authors. 


## Table of Contents 
  * [Facial Expression - Image and Video Datasets](#facial-expression---image-and-video-datasets)
    + [Infant Databases](#infant-databases)
  * [Interaction](#interaction)
  * [Mental Health Labels](#mental-health-labels)
    + [Beyond Visual](#beyond-visual)
    + [Infant Databases](#infant-databases-1)
  * [Tools](#tools)
    + [Facial Action Units and more](#facial-action-units-and-more)
    + [Facial Landmarks only](#facial-landmarks-only)
  * [Some Face Models](#some-face-models)
  * [2DO](#2do)
  * [Related Sources](#related-sources)
  * [Contact](#contact)


## Notation

Information is ordered according to the following scheme:
- name + link
  - short description
  - annotations: ...
  - reference: ...
  - available: 
    - ✅ Free to download
    - 📧 Free upon request (most are for academics only 🎓) 
    - 🔒 not publicly available
    - 💰 if payment is required
    - ❌ No longer available 


## Facial Expression - Image and Video Datasets
In the following datasets contain images or video with labels of facial expression in no particular order:

- [Aff-Wild2 database](https://ibug.doc.ic.ac.uk/resources/aff-wild2/)
  - 541 videos of around 2.6M frames (in the wild) (big diversity in terms of subjects' ages, ethnicities and nationalities)
  - 554 subjects (326 of which are male and 228 female)
  - annotations: seven basic expressions (i.e., happiness, surprise, anger, disgust, fear, sadness and the neutral state), twelve action units (AUs 1,2,4,6,7,10,12,15,23,24,25,26) and valence and arousal
  - reference: several papers are listed on the webpage "must cite all following papers"
  - 📧 availability: upon request
- [AffectNet](https://www.mohammadmahoor.com/pages/databases/affectnet/) 
  - <1M facial images
  - annotations: ca. half (~440K) annotated presence of seven discrete facial expressions
  - reference: "AffectNet: A New Database for Facial Expression, Valence, and Arousal Computation in the Wild," Mollahosseini et al., 2017 
  - 📧 available: upon request for academics
- [The Japanese Female Facial Expression (JAFFE) Dataset](https://www.kasrl.org/jaffe_download)
   - 213 images, 10 Japanese women, gray scale (Several images of each expression for each expresser)
   - annotations: averaged semantic ratings on 6 facial expressions by 60 Japanese viewers, 7 Posed Facial Expressions (6 basic facial expressions + 1 neutral) 
   - reference: "Coding Facial Expressions with Gabor Wavelets," Lyons, Michael J., Miyuki Kamachi, and Jiro Gyoba, 1998
   - ✅ available: free to download
- [RAVDESS](https://zenodo.org/record/1188976#.ZCPaFC8Robx) (2018):
  - The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) 
  - 7356 recordings were each rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals 
  - to verify: [kaggle link](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
  - subjects: 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent
  - annotations: emotion + intensity
    - Speech emotions: calm, happy, sad, angry, fearful, surprise, and disgust, each at two levels intensity (normal, strong) + neutral expression.
  - ✅ available: under a Creative Commons Attribution 
- [SAMM: A Spontaneous Micro-Facial Movement Dataset](https://e-space.mmu.ac.uk/617069/) [link](https://helward.mmu.ac.uk/STAFF/m.yap/dataset.php) 
  - video recordings of 32 participants watching seven stimuli 
  - annotations: FACS (Facial Action Units), 7 emotions (and more)
  - reference: Davison, AK, Lansley, C, Costen, N, Tan, K and Yap, MH (2018) SAMM: A Spontaneous Micro-Facial Movement Dataset. IEEE Transactions on Affective Computing, 9 (1). pp. 116-129. ISSN 1949-3045 
  - 📧 available: upon request
  <!-- They compare to: Polikovsky et al. [13] SMIC [14] USF-HD [15] CASME [16] CASME II [17] -->
- SAMM Long Videos: A Spontaneous Facial Micro- and Macro-Expressions Dataset [link](https://helward.mmu.ac.uk/STAFF/m.yap/dataset.php) 
  - extension of SAMM. 147 long videos with 343 macro-expressions and 159 micro-expressions
  - annotations: FACS, emotions
  - reference: Yap, C.H., Kendrick, C. and Yap, M.H., 2020, November. Samm long videos: A spontaneous facial micro-and macro-expressions dataset. In 2020 15th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2020) (pp. 771-776). IEEE. 
  - 📧 available: upon request
- [FEAFA+: An Extended Well-Annotated Dataset for Facial Expression Analysis and 3D Facial Animation](https://www.iiplab.net/feafa+/)
 - tbd
   
### Infant Databases
- [The City Infant Faces Database: A validated set of infant facial expressions (CIF)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5809537/)
  - 60 photographs of positive infant faces, 54 photographs of negative infant faces, and 40 photographs of neutral infant faces.
  - annotations: 
  - reference: Webb R, Ayers S, Endress A. The City Infant Faces Database: A validated set of infant facial expressions. Behav Res Methods. 2018 Feb; 50(1):151-159. doi: 10.3758/s13428-017-0859-9. PMID: 28205132; PMCID: PMC5809537 
  - 📧 available: upon request (for researchers)
- [Tromsø Infant Faces Database )(TIF)](https://uit.no/project/norbaby/database)
  - 119 images of infant facial expressions
  - 18 subjects (age 4-12 months)
  - annotations: 4-7 facial expressions (happy & sad for all, for some: anger, fear, suprise or disgust) validated by over 700 participants 
  - reference: "The Tromso Infant Faces database (TIF): development, validation and application to assess parenting experience on clarity and intensity ratings", Maack JK, Bohne A, Nordahl D, Livsdatter L, Overvoll M, Wang CA and Pfuhl G (2017)
  - 📧 available: upon request for academics
- [The Child Affective Facial Expressions Set (CAFE)](https://www.childstudycenter-rutgers.com/the-child-affective-facial-expression-se)
  - 1200 photographs
  - subjects: over 100 children (ages 2-8)
  - annotations: 7 different facial expressions - happy, angry, sad, fearful, surprise, neutral, and disgust.
  - reference: "The Child Affective Facial Expression (CAFE) Set: Validity and reliability from untrained adults", LoBue, V. & Thrasher, C., 2015
  - 📧 available: upon request for academics
- [Cry, Laugh, or Angry? Dataset](https://data.mendeley.com/datasets/hy969mrx9p/1) (Mendeley Data, 2025)
  - 1,600 manually labeled images (expanded to over 26,000 with augmentation)
  - annotations: four categories: angry, cry, laugh, and normal
  - reference: Hasan, Md. Mehedi; SHAHRIARE, EMON; Rashid, Maria; Rifat, MD Sayed Islam; Siddik, Md. Redoy; Bijoy, Md Hasan Imam (2025), “Cry, Laugh, or Angry? A Benchmark Dataset for Computer Vision-Based Approach to Infant Facial Emotion Recognition”, Mendeley Data, V1, doi: 10.17632/hy969mrx9p.1
  - ✅ available: free to download
- [Infant Facial Expression of Pain Intensity (IFEPI)](https://zenodo.org/records/14011791)
  - 25,000 spontaneous images of infant facial expressions of pain intensity, focus on infants’ pain-related facial expressions, intended for medical and affective computing applications (Pakistan, with collaboration from UNICEF)
  - annotations: facial expressions of pain intensity, (check if labels are given for Neonatal Facial Coding System (NFCS))
  - reference: tdb
  - available: tbd
- ChildEFES (Child Emotion Facial Expression Set)
  - 1,985 stimuli (photos and videos) of 4–6-year-olds expressing posed and induced emotions
  - annotations: FACS
  - reference: tdb
  - available: tbd
- Children’s Emotions Dataset (2025)
  - Focused on children aged 10–12
  - annotations: 7 emotions, FACS (?)
  - reference: tdb
  - available: tbd
- CMED (Child Micro-Expression Dataset, 2025)
  - videos subtle and spontaneous micro-expressions in children
  - annotations: tbd
  - reference: tdb
  - available: tbd

## Interaction
Focus on human interaction
- [Cardiff Conversation Database (CCDb)](https://ccdb.cs.cf.ac.uk/)
  - audio-visual natural conversation database with 2D and 3D data.
  - annotations: tbd
  - reference: tbd, 2013
  - 📧 available: upon request for academics


## Mental Health Labels

Datasets with labels related to health and mental health.

- [Distress Analysis Interview Corpus (DAIC)](https://aclanthology.org/L14-1421/)
  - The Distress Analysis Interview Corpus of human and computer interviews
  - annotations: PHQ-8 (depression), and more
  - reference: Gratch J, Artstein R, Lucas GM, Stratou G, Scherer S, Nazarian A, Wood R, Boberg J, DeVault D, Marsella S, Traum DR. The Distress Analysis Interview Corpus of Human and Computer Interviews. In Proceedings of LREC 2014 May (pp. 3123-3128).
  - ❌ available: does not seem to be available as a whole
- [DAIC-WOZ Database](https://dcapswoz.ict.usc.edu/)
  - description:
    - subset of the larger Distress Analysis Interview Corpus (DAIC)
    - virtual interviewer. 189 sessions of interactions ranging between 7-33 minutes (average is 16 minutes), contains features extracted from video (not actual image and video footage)
    - transcripts of the interaction, participant audio files, and facial expressions (FACS-encoded by OpenFace 2.0)
  - annotations: PHQ-8 all items (depression), gender 
  - reference: DeVault, D., Artstein, R., Benn, G., Dey, T., Fast, E., Gainer, A., Georgila, K., Gratch, J., Hartholt, A., Lhommet, M., Lucas, G., Marsella, S., Morbini, F., Nazarian, A., Scherer, S., Stratou, G., Suri, A., Traum, D., Wood, R., Xu, Y., Rizzo, A., and Morency, L.-P. (2014). “SimSensei kiosk: A virtual human interviewer for healthcare decision support.” In Proceedings of the 13th International Conference on Autonomous Agents and Multiagent Systems (AAMAS’14), Paris.
  - 📧 available: upon request for academics
- [Extended DAIC Database](https://dcapswoz.ict.usc.edu/)
  - extended version of DAIC-WOZ database for depression and PTSD assessment (was used for the AVEC 2019)
  - annotations: tbd
  - reference: Ringeval, Fabien, Björn Schuller, Michel Valstar, Nicholas Cummins, Roddy Cowie, Leili Tavabi, Maximilian Schmitt et al. “Avec 2019 workshop and challenge: State-of-mind, detecting depression with ai, and cross-cultural affect recognition.” In Proceedings of the 9th International on Audio/Visual Emotion Challenge and Workshop, pp. 3-12. ACM, 2019. 
  - 📧 available: upon request for academics
- [MultiWOZ - A Large-Scale Multi-Domain Wizard-of-Oz Dataset for Task-Oriented Dialogue Modelling](https://aclanthology.org/D18-1547/)
  - 10k dialogues (3,406 single-domain, 7,032 multi-domain dialogues) 
  - annotations: tbd
  - reference: Paweł Budzianowski, Tsung-Hsien Wen, Bo-Hsiang Tseng, Iñigo Casanueva, Stefan Ultes, Osman Ramadan, and Milica Gašić. 2018. MultiWOZ - A Large-Scale Multi-Domain Wizard-of-Oz Dataset for Task-Oriented Dialogue Modelling. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing, pages 5016–5026, Brussels, Belgium. Association for Computational Linguistics.
  - 📧 available: upon request for academics
- [YouTube Facial Palsy (YFP) Database](https://sites.google.com/view/yfp-database#h.p_DaUvW9mE7B_g) (2018)
  - 32 videos of 21 patients from YouTube, and a few patients have multiple videos
  - annotations: Manually labeled local palsy regions, location (eyes, mouth), intensity (low or high)
  - reference: GEE-SERN JISON HSU, JIUNN-HORNG KANG, WEN-FONG HUANG, Deep Hierarchical Network With Line Segment Learning for Quantitative Analysis of Facial Palsy, IEEE Access, vol. 7, 4833-4842, Dec. 2018
  - 📧 available: upon request for academics
- [Turkish Audio-Visual Bipolar Disorder Corpus](https://ieeexplore.ieee.org/document/8470362/&ved=2ahUKEwi-1qunureQAxUO2wIHHYG7MOoQFnoECB0QAQ&usg=AOvVaw0Gky0kRbgXgS4vTZKVQ5cC)
  - description: was part of an AVEC 2018, audio-visual Bipolar Disorder (BD) corpus for the affective computing and psychiatric communities 
  - annotations: Bipolar Disorder (binary labels)
  - reference: "The Turkish Audio-Visual Bipolar Disorder Corpus", Ciftci, Kaya (2018)
  - ❌ has become unavailable. (Permitted use ran out, listed for completeness.) 
 <!-- looks interesting, but no files: "Facial Paralysis Dataset" https://ieee-dataport.org/documents/facial-paralysis-dataset#files-->

### Infants

- CALMED Dataset (2023)
  – A multimodal annotated dataset for emotion detection in children with autism aged 8–12
- Hugging Rain Man (HRM) Dataset (2024)
  - Contains manually annotated facial Action Units for both ASD and typically developing children
- MMASD (DE-ENIGMA) – Combines visual, auditory, and behavioral features for autism intervention research


### Beyond Visual

- [EMU: Early Mental Health Uncovering](https://github.com/mltlachac/EMU) (2021)
  - availibility: ?
- [The DepreST Call and Text (DepreST-CAT) dataset](https://github.com/mltlachac/DepreST-CAT) [project page](https://emutivo.wpi.edu/index.php/data/)
  - call and text logs
  - annotations: demographics, PHQ-9 (depression scores), and GAD-7 (anxiety screening scores) from over 369 Prolific crowd-sourced participants
  - reference: ML Tlachac, Ricardo Flores, Miranda Reisch, Katie Housekeeper, Elke Rundensteiner, “DepreST-CAT: Retrospective Smartphone Call and Text Logs Collected During the COVID-19 Pandemic to Screen for Mental Illnesses”, ACM Proceedings on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT), vol. 6, no. 2,  2022.
  - available: free to download ? (free for academic use)
- [Student Suicidal Ideation and Depression Detection (StudentSADD) dataset](https://emutivo.wpi.edu/index.php/data/)
  - annotations:
  - reference:
  - available: ?
- Audio [speech data with depression labels](https://github.com/speechandlanguageprocessing/ICASSP2022-Depression)
- [Depresjon](https://datasets.simula.no/depresjon/) [kaggle](https://www.kaggle.com/datasets/arashnic/the-depression-dataset) (2018):
  - description: tbd 
  - annotations: tbd
  - reference: A Motor Activity Database of Depression Episodes in Unipolar and Bipolar Patients:  motor activity recordings of 23 unipolar and bipolar depressed patients and 32 healthy controls.
  - ✅ availability: freel to download
- [DASPS database ](https://ieee-dataport.org/open-access/dasps-database) (2021):
  - raw EEG data collected from the 23 participants during anxiety. "We provided a matlab script for the segmentation of each EEG signal into 6 segments corresponding to the 6 situations.".




### Infant Databases
- [A Dataset of Eye Movements for the Children with Autism Spectrum Disorder](https://zenodo.org/records/2647418)
  - 300 natural scene images and the corresponding eye movement
  - 14 children with ASD and 14 healthy controls
  - reference: H. Duan, G. Zhai, X. Min, Z. Che, Y. Fang, X. Yang, J. Gutiérrez, P. Le Callet, "A Dataset of Eye Movements for the Children with Autism Spectrum Disorder", ACM Multimedia Systems Conference (MMSys'19), Jun. 2019.
  - ✅ available: free to download
- [The Craniofacial microsomia: Longitudinal Outcomes in Children pre-Kindergarten (CLOCK)](https://pubmed.ncbi.nlm.nih.gov/30621445/) (2019)
  - study is a longitudinal cohort study of neurobehavioral outcomes in infants and toddlers with craniofacial microsomia (CFM)
  - 108 cases and 84 controls
  - reference: Luquetti DV, Speltz ML, Wallace ER, Siebold B, Collett BR, Drake AF, Johns AL, Kapp-Simon KA, Kinter SL, Leroux BG, Magee L, Norton S, Sie K, Heike CL. Methods and Challenges in a Cohort Study of Infants and Toddlers With Craniofacial Microsomia: The Clock Study. Cleft Palate Craniofac J. 2019 Aug;56(7):877-889. doi: 10.1177/1055665618821014. Epub 2019 Jan 8. PMID: 30621445; PMCID: PMC6996714.
  - available: ?
- [MIAMI](https://pubmed.ncbi.nlm.nih.gov/26640622/) (2015)
  - head movement in mothers and infants during the Still Face paradigm
  - 42 infants: 4-month-old infants and their mothers
  - reference: Hammal Z, Cohn JF, Messinger DS. Head Movement Dynamics During Play and Perturbed Mother-Infant Interaction. IEEE Trans Affect Comput. 2015 Oct-Dec;6(4):361-370. doi: 10.1109/TAFFC.2015.2422702. Epub 2015 Apr 13. PMID: 26640622; PMCID: PMC4666546.
  - available: ?


## Tools
### Facial Action Units and more
- [OpenFace](https://openface-api.readthedocs.io/en/latest/)
- [Python Facial Expression Analysis Toolbox (Py-Feat)](https://py-feat.org/pages/intro.html)
- PyAFAR: Python-based Automated Facial Action Recognition library for use in Infants and Adults: [website](https://pyafar.org/), [github](https://github.com/AffectAnalysisGroup/PyAFAR)

### Facial Landmarks only
- [dlib](http://dlib.net/)
- [Mediapipe](https://developers.google.com/mediapipe/)

## Some Face Models
Publicly available models.
- [Candide-3](candide3.md): 3D wireframe model: 113 3D vertices connected with triangles, parameters for changing of the shape and expression of the 3D face
- [Basel Face Model](https://faces.dmi.unibas.ch/bfm/) - 3D Morphable Face Model (Shape and Texture)


## Related Sources

1. Mental Health Datasets
Separate repository to come

2. Looking for Human Motion and Sports?
Check out this repository [HumanMotionCollection](https://github.com/stellagra/HumanMotionCollection)

3. Related to Facial Expressions
  - [Affective Computing](https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange)
  - more datasets: [here](https://emutivo.wpi.edu/index.php/data/)
  - [survey](https://www.mdpi.com/1424-8220/22/4/1524)
  - more [face rec databases](https://www.face-rec.org/databases/)


## 2DO
- check all AVEC, e.g. [AVEC2013](https://github.com/chkche1/avec2013), [AVEC2019](https://sites.google.com/view/avec2019/home) for availabilty
- 💰 [Binghamton Face Databases](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
- [list of databases](https://mohammadmahoor.com/pages/databases/)




## Contact
[Stella Grasshof](https://pure.itu.dk/en/persons/stella-grasshof) - IT University of Copenhagen

<p align="right">[<a href="#readme-top">back to top</a>]</p>
