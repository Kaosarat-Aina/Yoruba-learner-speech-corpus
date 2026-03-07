
# Project Title
# Yoruba Learner Speech Corpus (YLSC)
_The first phonemically and tonally annotated speech corpus of Yoruba learner pronunciation designed for linguistic research and CAPT development._

The Yoruba learner Speech Corpus is a pioneering, phonemically and tonally annotated dataset designed to support research in Second Language Acquisition (SLA), Automatic Speech Recognition (ASR), and Computer-Assisted Pronunciation Training (CAPT). By capturing authentic learner speech with expert phonetic diagnostics, this project addresses the significant gap in resources for tonal African languages.

**Project lead: Kaosarat Aina**, **Indiana University Bloomington**

**Contact: kbaina@iu.edu**

# Overview
The Yoruba Learner Speech Corpus (YLSC) is a developing dataset of speech produced by second-language and heritage learners of Yoruba. 

Learning a second language (L2) is a complex process where speaking proficiency often serves as the foundation for learner confidence. However, learners frequently lack immediate corrective feedback during self-study. While commercial CAPT tools exist, their proprietary nature limits research and modification. This corpus provides an open-source foundational resource for developing robust, diagnostic feedback systems.

# Research Motivation
* **Tonal Complexity**: Yoruba's three-way tonal contrast (High, Mid, and Low) presents a steep challenge for L2 learners, particularly those from non-tonal L1 backgrounds.
* **Segmental Challenges**: Beyond tones, learners often struggle with unique Yoruba phonemes, such as co-articulated labial-velar stops ([ɡb], [kp]) and the Advanced Tongue Root (±ATR) vowel harmony system.
* **Native vs. Learner Data**: Existing Yoruba corpora are designed for native speech, lacking the specific phonological errors—such as vowel harmony violations or tonal misassignments—inherent to learners.
* **Diagnostic Gaps**: Current research requires error-annotated corpora to move beyond simple "pass/fail" error detection to precise phonetic diagnosis.


# Corpus Design
* Participants: 60 L2 and heritage learners from 4 major universities (Indiana, Howard, Georgia, Wisconsin), spanning elementary, intermediate, and advanced levels.
  
* Phonetic Targets: Balanced representation of Yoruba phonology, including:
  * Suprasegmentals: Tonal combinations and kontures.
  * Segmentals: Challenging consonants ([ɡb], [kp], [p]) and ATR vowel contrasts.
  * Syntax: Diverse structures including questions and imperatives.

* Expert Annotation: Three trained native Yoruba phoneticians provide binary accuracy values (0-1) and specific diagnostic transcriptions across phoneme, tone, and insertion layers.

* For a deep dive into our sampling strategy, phonetic targets, and technical specs, see the [YLSC_Corpus_Design](./docs/YLSC_Corpus_Design_and_Methodology.pdf).

# Planned Corpus Structure

The repository is organized to facilitate easy integration with machine learning pipelines:

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
   contributing/

Each recording file contains identifiers for sentence number, textbook chapter, and speaker ID, ensuring consistent alignment between audio, annotations, and metadata.

# Project Roadmap
The Yoruba Learner Speech Corpus is being developed in stages to support both linguistic research and speech technology development.

## Phase 1 – Corpus Design and Pilot Data
* Develop corpus design and annotation guidelines
* Conduct pilot recordings with Yoruba learners
* Develop annotation workflow and scripts

## Phase 2 – Data Collection
* Record learner speech across partner universities
* Collect recordings across proficiency levels (elementary, intermediate, advanced)
* Organize audio files and metadata

## Phase 3 – Annotation
* Annotate recordings for phonemic accuracy, lexical tone, and insertion errors
* Conduct inter-annotator agreement analysis
* Refine annotation guidelines

## Phase 4 – Corpus Release
* Prepare structured dataset and documentation
* Release pilot corpus subset for research use
* Publish corpus description paper

## Phase 5 – Applications
* Develop computational models for tone and pronunciation error detection
* Support development of CAPT systems for Yoruba learners
* Expand corpus with additional learner data

# How to cite

While the project is ongoing, please cite the research proposal

Aina, K. (2026). _A Resource for Pronunciation Feedback Systems: Creating a Phonemically Annotated Speech Corpus of Yoruba Language Learner Speech_. Project Proposal, Indiana University.

Future releases of the corpus will include a versioned dataset citation and DOI to support reproducible research

# Project status

* Data collection: in progress
* Annotation scheme: draft
* Pilot dataset release: planned
