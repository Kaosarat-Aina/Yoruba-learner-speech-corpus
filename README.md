
# Project Title
# Yoruba Learner Speech Corpus (YLSC)
_The first phonemically and tonally annotated speech corpus of Yoruba learner pronunciation designed for linguistic research and CAPT development._

A developing speech corpus of Yoruba L2 and heritage learner productions designed to support research on sound and tone acquisition, phonetics/phonology, and computer-assisted pronunciation training (CAPT) for tonal and under-resourced languages.

**Project lead: Kaosarat Aina**, **Indiana University Bloomington**

**Contact: kbaina@iu.edu**

# Overview
The Yoruba Learner Speech Corpus (YLSC) is a developing dataset of speech produced by second-language and heritage learners of Yoruba. The corpus is designed to support research on learner pronunciation, phonological acquisition, and computer-assisted pronunciation training (CAPT) for Yoruba.

The project aims to create the first phonemically and tonally annotated learner speech corpus for Yoruba. Each recording will be annotated for both segmental pronunciation (consonants and vowels) and lexical tone production, enabling detailed analyses of how learners acquire the sound system of a tonal language.

Beyond linguistic research, the corpus is intended to support the development of automated pronunciation feedback systems capable of identifying and providing feedback on both phonemic and tonal errors in learner speech. The dataset will therefore serve as a resource for research in second language phonology, computational phonetics, and speech technology for under-resourced languages.

# Research Motivation
Pronunciation is one of the most challenging aspects of second language learning and is closely tied to learners’ confidence and communicative ability. However, many learners study languages outside environments where the language is widely spoken, limiting opportunities for practice and immediate corrective feedback. Computer-assisted pronunciation training (CAPT) systems can help address this gap, but their development depends heavily on annotated learner speech corpora that capture real pronunciation errors.

While several speech and text resources exist for Yoruba, they are primarily designed for native speech or general language processing tasks and do not capture the pronunciation patterns and errors typical of language learners. This limits their usefulness for research in second language acquisition and pronunciation feedback systems

The Yoruba Learner Speech Corpus addresses this gap by creating a dataset specifically designed for learner pronunciation analysis and automated feedback systems. By providing phonemic and tonal annotations of learner speech, the corpus will support research in L2 phonology, pronunciation assessment, CAPT development, and speech technology for tonal and under-resourced languages.

# Corpus Design
The Yoruba Learner Speech Corpus will contain speech recordings from second-language and heritage learners of Yoruba recruited from four universities in the United States:
* Indiana University
* Howard University
* University of Georgia
* University of Wisconsin

Participants will be sampled across three proficiency levels:
* Elementary
* Intermediate
* Advanced
  
Five students will be recruited at each level from each university, resulting in 60 learners in total. This design captures pronunciation variation across different stages of language learning and across speakers with different first-language backgrounds.

Each participant will record 100 sentences drawn from two Yoruba language textbooks used in instructional settings. Sentences are selected to represent a wide range of:

* Phonemic contrasts
* Tonal combinations
* Syntactic structures (questions, declaratives, exclamations, imperatives)

With 60 speakers producing 100 sentences each, the corpus will contain approximately 6,000 recorded sentences

Recordings will be made in a controlled recording environment and stored using a structured file-naming system that includes sentence number, source chapter, and speaker ID. The corpus will preserve natural learner speech, including hesitations, false starts, and pronunciation errors, as these are essential for training pronunciation feedback systems.

Speech recordings will be annotated by trained native Yoruba phoneticians using multi-tier annotation. Annotation layers include:
phoneme accuracy
lexical tone accuracy
phoneme insertions
detailed mispronunciation labels
This annotation design allows the corpus to support both linguistic analysis and computational pronunciation-feedback models.

# Planned Corpus Structure

audio/
   recordings/

annotations/
   phoneme_annotations/
   tone_annotations/
   insertion_annotations/
   sound_heard/

metadata/
   speaker_information/
   recording_metadata/

scripts/
   praat/
   r_analysis/

docs/
   annotation_guidelines/
   corpus_description/

Each recording file contains identifiers for sentence number, textbook chapter, and speaker ID, ensuring consistent alignment between audio, annotations, and metadata.

# Project Roadmap
The Yoruba Learner Speech Corpus is being developed in stages to support both linguistic research and speech technology development.

# Phase 1 – Corpus Design and Pilot Data
* Develop corpus design and annotation guidelines
* Conduct pilot recordings with Yoruba learners
* Develop annotation workflow and scripts

# Phase 2 – Data Collection
* Record learner speech across partner universities
* Collect recordings across proficiency levels (elementary, intermediate, advanced)
* Organize audio files and metadata

# Phase 3 – Annotation
* Annotate recordings for phonemic accuracy, lexical tone, and insertion errors
* Conduct inter-annotator agreement analysis
* Refine annotation guidelines

# Phase 4 – Corpus Release
* Prepare structured dataset and documentation
* Release pilot corpus subset for research use
* Publish corpus description paper

# Phase 5 – Applications
* Develop computational models for tone and pronunciation error detection
* Support development of CAPT systems for Yoruba learners
* Expand corpus with additional learner data

# How to cite
If you use or reference the Yoruba Learner Speech Corpus in your research, please cite the project as follows:

Aina, Kaosarat. (in preparation). Yoruba Learner Speech Corpus (YLSC). Indiana University Bloomington.

Future releases of the corpus will include a versioned dataset citation and DOI to support reproducible research

# Project status

* Data collection: in progress
* Annotation scheme: draft
* Pilot dataset release: planned
