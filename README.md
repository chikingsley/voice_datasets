# voice_datasets
A comprehensive list of open source voice and music datasets. I released this for the talk @ the [VOICE Summit 2019.](https://github.com/jim-schwoebel/voice_gender_detection)

![](https://media.giphy.com/media/3o6ozifkiTecWsJOFO/giphy.gif)

## Audio datasets
This repository tracks open datasets for speech, voice, and audio events/music.

## Table of contents
* [How this list is organized](#how-this-list-is-organized)
* [Maintenance and curation](#maintenance-and-curation)
* [Browse quickly](#browse-quickly)
* [Pattern references](#pattern-references)
* [Full catalog](#full-catalog)
* [Upstream provenance](#upstream-provenance)
* [Learn more](#learn-more)

## How this list is organized
* The quick index is optimized for discovery by task and language.
* The full catalog keeps the complete A-Z dataset list in collapsible sections.
* New curated additions should be reflected in both places when possible.

## Maintenance and curation
This fork is actively maintained and accepts vetted additions from community issues.

When adding a dataset, please include:
* A direct dataset URL (not only a paper link).
* Licensing/access details (free, commercial, gated, etc.).
* A short description (language, task, and size/hours if known).
* Expected quick-index placement (`By task` and `By language`).

Link health:
* Pull requests run automated Markdown link checks on changed files.
* A scheduled full link scan runs weekly and publishes a report artifact.

## Browse quickly
This section is a curated index (not exhaustive). Use the full catalog for complete coverage.

### By task
* ASR and transcription: [Common Voice](https://commonvoice.mozilla.org/en/datasets), [Librispeech](https://www.openslr.org/12), [SPGISpeech](https://datasets.kensho.com/datasets/spgispeech), [VoxPopuli](https://github.com/facebookresearch/voxpopuli), [Ted-LIUM](https://www.openslr.org/51/), [People's Speech](https://mlcommons.org/en/peoples-speech/).
* Emotion and affect: [IEMOCAP](https://sail.usc.edu/iemocap/iemocap_release.htm), [CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D), [RAVDESS](https://zenodo.org/record/1188976#.XrC7a5NKjOR), [Emo-DB](https://github.com/audeering/emodb), [TESS](https://tspace.library.utoronto.ca/handle/1807/24487), [MELD](https://github.com/SenticNet/MELD).
* Clinical and health speech: [Coswara](https://github.com/iiscleap/Coswara-Data), [CUCO Surgery Speech Corpus](https://zenodo.org/records/11654546), [NeuroVoz](https://zenodo.org/records/13647600), [Parkinson's speech dataset](https://archive.ics.uci.edu/dataset/301/parkinson+speech+dataset+with+multiple+types+of+sound+recordings), [SEP-28k](https://www.kaggle.com/datasets/ikrbasak/sep-28k), [Parrot Radiology ASR EN](https://huggingface.co/datasets/ysdede/parrot-radiology-asr-en).
* Speaker and diarization: [VoxCeleb](https://github.com/andabi/voice-vector), [VOiCES Dataset](https://iqtlabs.github.io/voices/), [Awesome_Diarization](https://github.com/jim-schwoebel/awesome-diarization).
* Speech enhancement and separation: [CHIME](https://archive.org/details/chime-home), [WHAM! and WHAMR!](https://arxiv.org/abs/1910.10279), [LibriMix](https://github.com/JorisCos/LibriMix), [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix), [Microsoft Scalable Noisy Speech Dataset](https://github.com/microsoft/MS-SNSD).
* Commands and keyword spotting: [Speech Commands Dataset](https://research.google/blog/launching-the-speech-commands-dataset/), [Free Spoken Digit Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset), [AudioMNIST](https://github.com/soerenab/AudioMNIST), [Multilingual Spoken Words Corpus (MSWC)](https://mlcommons.org/datasets/multilingual-spoken-words/).
* Human non-speech vocal sounds: [VocalSound](https://github.com/YuanGongND/vocalsound), [VIVAE](https://zenodo.org/record/4066235), [Nonverbal Vocalization Dataset](https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset).
* Dataset directories and meta-lists: [ASR datasets](https://github.com/robmsmt/ASR_Audio_Data_Links), [OpenSLR](https://openslr.org), [SER Datasets](https://github.com/SuperKogito/SER-datasets), [ISMIR Datasets List](https://www.ismir.net/resources/datasets/).

### By language
Language grouping rules used here:
* `Multilingual` means the dataset is intentionally cross-lingual.
* `Primary language` means one dominant language is documented.
* `Code-switched` means mixed-language utterances are the core design.
* `Language-agnostic` means nonverbal audio, mixed utility sets, or directories.

#### Multilingual and cross-lingual
* [Common Voice](https://commonvoice.mozilla.org/en/datasets), [VoxPopuli](https://github.com/facebookresearch/voxpopuli), [Multilingual Spoken Words Corpus (MSWC)](https://mlcommons.org/datasets/multilingual-spoken-words/), [OpenSLR](https://openslr.org), [People's Speech](https://mlcommons.org/en/peoples-speech/).

#### Primary language: English
* [Librispeech](https://www.openslr.org/12), [Ted-LIUM](https://www.openslr.org/51/), [SPGISpeech](https://datasets.kensho.com/datasets/spgispeech), [RAVDESS](https://zenodo.org/record/1188976#.XrC7a5NKjOR), [VOiCES Dataset](https://iqtlabs.github.io/voices/).

#### Primary language: Arabic
* [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/), [ANAD](https://www.kaggle.com/suso172/arabic-natural-audio-dataset), [BAVED](https://www.kaggle.com/a13x10/basic-arabic-vocal-emotions-dataset).

#### Primary language: Spanish (Castilian)
* [CUCO Surgery Speech Corpus](https://zenodo.org/records/11654546), [NeuroVoz](https://zenodo.org/records/13647600).

#### Primary language: Persian
* [Persian Consonant Vowel Combination (PCVC) Speech Dataset](https://github.com/S-Malek/PCVC), [ShEMO](https://github.com/mansourehk/ShEMO).

#### Primary language: Korean
* [Korean Read Speech Corpus](https://github.com/deeplyinc/Korean-Read-Speech-Corpus).

#### Primary language: Japanese
* [Keio-ESD](http://research.nii.ac.jp/src/en/Keio-ESD.html).

#### Primary language: German
* [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/), [Emo-DB](https://github.com/audeering/emodb).

#### Primary language: Italian
* [EMOVO](http://voice.fub.it/activities/corpora/emovo/index.html).

#### Primary language: Urdu
* [URDU-Dataset](https://github.com/siddiquelatif/urdu-dataset).

#### Code-switched
* [MediBeng](https://huggingface.co/datasets/pr0mila-gh0sh/MediBeng) (Bengali-English).

#### Language-agnostic and nonverbal
* [VocalSound](https://github.com/YuanGongND/vocalsound), [VIVAE](https://zenodo.org/record/4066235), [Nonverbal Vocalization Dataset](https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset), [ASR datasets](https://github.com/robmsmt/ASR_Audio_Data_Links), [SER Datasets](https://github.com/SuperKogito/SER-datasets).

## Pattern references
* [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - topic-first TOC and category section pattern.
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) - canonical awesome-list structure and contribution conventions.
* GitHub `<details>` sections - useful for long lists while keeping quick index sections visible.

## Full catalog
<details open>
<summary><strong>Speech datasets (A-Z)</strong></summary>

* [AESDD](https://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/) - around 500 utterances by a diverse group of actors (over 5 actors) simlating various emotions.
* [ANAD](https://www.kaggle.com/suso172/arabic-natural-audio-dataset) - 1384 recording by multiple speakers; 3 emotions: angry, happy, surprised.
* [Arabic Speech Corpus](http://en.arabicspeechcorpus.com/) - The Arabic Speech Corpus (1.5 GB) is a Modern Standard Arabic (MSA) speech corpus for speech synthesis. The corpus contains phonetic and orthographic transcriptions of more than 3.7 hours of MSA speech aligned with recorded speech on the phoneme level. The annotations include word stress marks on the individual phonemes. 
* [ASR datasets](https://github.com/robmsmt/ASR_Audio_Data_Links) - A list of publically available audio data that anyone can download for ASR or other speech activities
* [AVID](https://zenodo.org/records/10524873) - Audio-visual dataset shared on Zenodo for speech and multimodal research tasks.
* [AudioMNIST](https://github.com/soerenab/AudioMNIST) - The dataset consists of 30000 audio samples of spoken digits (0-9) of 60 different speakers
* [Awesome_Diarization](https://github.com/jim-schwoebel/awesome-diarization) - A curated list of awesome Speaker Diarization papers, libraries, datasets, and other resources. 
* [BAVED](https://www.kaggle.com/a13x10/basic-arabic-vocal-emotions-dataset) - 1935 recording by 61 speakers (45 male and 16 female).
* [CaFE](https://www.gel.usherbrooke.ca/audio/cafe.htm) - 6 different sentences by 12 speakers (6 fmelaes + 6 males).
* [Common Voice](https://commonvoice.mozilla.org/en/datasets) - Common Voice is Mozilla's initiative to help teach machines how real people speak. 12GB in size; spoken text based on text from a number of public domain sources like user-submitted blog posts, old books, movies, and other public speech corpora.
* [CHIME](https://archive.org/details/chime-home) - This is a noisy speech recognition challenge dataset (~4GB in size). The dataset contains real simulated and clean voice recordings. Real being actual recordings of 4 speakers in nearly 9000 recordings over 4 noisy locations, simulated is generated by combining multiple environments over speech utterances and clean being non-noisy recordings. 
* [Coswara](https://github.com/iiscleap/Coswara-Data) - A database that contains respiratory sounds, namely, cough, breath, and speech of healthy and COVID-19 positive individuals.
* [CMU-MOSEI](https://github.com/CMU-MultiComp-Lab/CMU-MultimodalSDK) - 65 hours of annotated video from more than 1000 speakers and 250 topics; 6 Emotion (happiness, sadness, anger,fear, disgust, surprise) + Likert scale.
* [CMU-MOSI](https://github.com/CMU-MultiComp-Lab/CMU-MultimodalSDK) - 2199 opinion utterances with annotated sentiment; Sentiment annotated between very negative to very positive in seven Likert steps.
* [CMU Wilderness](https://github.com/festvox/datasets-CMU_Wilderness) - (noncommercial) - not available but a great speech dataset many accents reciting passages from the Bible.
* [CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D) - CREMA-D is a data set of 7,442 original clips from 91 actors. These clips were from 48 male and 43 female actors between the ages of 20 and 74 coming from a variety of races and ethnicities (African America, Asian, Caucasian, Hispanic, and Unspecified).
* [CUCO Surgery Speech Corpus](https://zenodo.org/records/11654546) - Spanish pre-/post-operative voice and speech corpus for upper airway surgery cases and controls.
* [DAPS Dataset](https://archive.org/details/daps_dataset) - DAPS consists of 20 speakers (10 female and 10 male) reading 5 excerpts each from public domain books (which provides about 14 minutes of data per speaker). 
* [Deep Clustering Dataset](https://www.merl.com/demos/deep-clustering) - Training deep discriminative embeddings to solve the cocktail party problem.
* [DEMoS](https://zenodo.org/record/2544829) - 9365 emotional and 332 neutral samples produced by 68 native speakers (23 females, 45 males); 7/6 emotions: anger, sadness, happiness, fear, surprise, disgust, and the secondary emotion guilt.
* [DES](https://doi.org/10.1006/brln.2000.2325) - 4 speakers (2 males and 2 females); 5 emotions: neutral, surprise, happiness, sadness and anger.
* [DIPCO](https://arxiv.org/abs/1909.13447) - Dinner Party Corpus - The participants were recorded by a single-channel close-talk microphone and by five far-field 7-microphone array devices positioned at different locations in the recording room. The dataset contains the audio recordings and human labeled transcripts of a total of 10 sessions with a duration between 15 and 45 minutes. 
* [EEKK](https://metashare.ut.ee/repository/browse/estonian-emotional-speech-corpus/f5e5fc91a0d311eebb4773db10791bcf07ff90a82bf541dbbb9ecf816da202fe/) - 26 text passage read by 10 speakers; 4 main emotions: joy, sadness, anger and neutral.
* [Emo-DB](https://github.com/audeering/emodb) - 800 recording spoken by 10 actors (5 males and 5 females); 7 emotions: anger, neutral, fear, boredom, happiness, sadness, disgust.
* [EmoFilm](https://zenodo.org/record/1326428) - 1115 audio instances sentences extracted from various films.
* [EmoSynth](https://zenodo.org/record/3727593) - 144 audio file labelled by 40 listeners; Emotion (no speech) defined in regard of valence and arousal.
* [Emotional Voices Database](https://github.com/numediart/EmoV-DB) - various emotions with 5 voice actors (amused, angry, disgusted, neutral, sleepy).
* [Emotional Voice dataset - Nature](https://www.nature.com/articles/s41562-019-0533-6) -  2,519 speech samples produced by 100 actors from 5 cultures. With large-scale statistical inference methods, we find that prosody can communicate at least 12 distinct kinds of emotion that are preserved across the 2 cultures. 
* [EmotionTTS](https://github.com/emotiontts/emotiontts_open_db) - Recordings and their associated transcriptions by a diverse group of speakers - 4 emotions: general, joy, anger, and sadness.
* [Emov-DB](https://mega.nz/#F!KBp32apT!gLIgyWf9iQ-yqnWFUFuUHg!mYwUnI4K) - Recordings for 4 speakers- 2 males and 2 females; The emotional styles are neutral, sleepiness, anger, disgust and amused.
* [EMOVO](http://voice.fub.it/activities/corpora/emovo/index.html) - 6 actors who played 14 sentences; 6 emotions: disgust, fear, anger, joy, surprise, sadness.
* [eNTERFACE05](http://www.enterface.net/enterface05/docs/results/databases/project2_database.zip) - Videos by 42 subjects, coming from 14 different nationalities; 6 emotions: anger, fear, surprise, happiness, sadness and disgust.
* [Free Spoken Digit Dataset](https://github.com/Jakobovski/free-spoken-digit-dataset) -4 speakers, 2,000 recordings (50 of each digit per speaker), English pronunciations.
* [Flickr Audio Caption](https://groups.csail.mit.edu/sls/downloads/flickraudio/) - 40,000 spoken captions of 8,000 natural images, 4.2 GB in size.
* [GEMEP corpus](https://www.unige.ch/cisa/gemep) - 10 actors portraying 10 states; 12 emotions: amusement, anxiety, cold anger (irritation), despair, hot anger (rage), fear (panic), interest, joy (elation), pleasure(sensory), pride, relief, and sadness. Plus, 5 additional emotions: admiration, contempt, disgust, surprise, and tenderness.
* [IEMOCAP](https://sail.usc.edu/iemocap/iemocap_release.htm) - 12 hours of audiovisual data by 10 actors; 5 emotions: happiness, anger, sadness, frustration and neutral.
* [ISOLET Data Set](https://data.world/uci/isolet) - This 38.7 GB dataset helps predict which letter-name was spoken — a simple classification task.
* [JL corpus](https://www.kaggle.com/tli725/jl-corpus) - 2400 recording of 240 sentences by 4 actors (2 males and 2 females); 5 primary emotions: angry, sad, neutral, happy, excited. 5 secondary emotions: anxious, apologetic, pensive, worried, enthusiastic.
* [Keio-ESD](http://research.nii.ac.jp/src/en/Keio-ESD.html) - A set of human speech with vocal emotion spoken by a Japanese male speaker; 47 emotions including angry, joyful, disgusting, downgrading, funny, worried, gentle, relief, indignation, shameful, etc.
* [Korean Read Speech Corpus](https://github.com/deeplyinc/Korean-Read-Speech-Corpus) - Korean read-speech dataset intended for ASR and speech representation research.
* [LEGO Corpus](https://www.ultes.eu/ressources/lego-spoken-dialogue-corpus/) - 347 dialogs with 9,083 system-user exchanges; emotions classified as garbage, non-angry, slightly angry and very angry.
* [Libriadapt](https://github.com/akhilmathurs/libriadapt) - It is primarily designed to faciliate domain adaptation research for ASR models, and contains the following three types of domain shifts in the data.
* [Libri-CSS](https://github.com/chenzhuo1011/libri_css) - derived from LibriSpeech by concatenating the corpus utterances to simulate a conversation and capturing the audio replays with far-field microphones.
* [LibriMix](https://github.com/JorisCos/LibriMix) - LibriMix is an open source dataset for source separation in noisy environments. It is derived from LibriSpeech signals (clean subset) and WHAM noise. It offers a free alternative to the WHAM dataset and complements it. It will also enable cross-dataset experiments.
* [Librispeech](https://www.openslr.org/12) - LibriSpeech is a corpus of approximately 1000 hours of 16Khz read English speech derived from read audiobooks from the LibriVox project.
* [LJ Speech](https://keithito.com/LJ-Speech-Dataset/) - This is a public domain speech dataset consisting of 13,100 short audio clips of a single speaker reading passages from 7 non-fiction books. A transcription is provided for each clip. Clips vary in length from 1 to 10 seconds and have a total length of approximately 24 hours.
* [Microsoft Scalable Noisy Speech Dataset](https://github.com/microsoft/MS-SNSD) - The Microsoft Scalable Noisy Speech Dataset (MS-SNSD) is a noisy speech dataset that can scale to arbitrary sizes depending on the number of speakers, noise types, and Speech to Noise Ratio (SNR) levels desired.
* [MSP-IMPROV](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Improv.html) - 20 sentences by 12 actors; 4 emotions: angry, sad, happy, neutral, other, without agreement
* [MSP Podcast Corpus](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html) - 100 hours by over 100 speakers - annotated with emotional labels using attribute-based descriptors (activation, dominance and valence) and categorical labels (anger, happiness, sadness, disgust, surprised, fear, contempt, neutral and other).
* [MediBeng](https://huggingface.co/datasets/pr0mila-gh0sh/MediBeng) - Synthetic Bengali-English code-switched healthcare speech dataset for ASR/TTS/MT tasks.
* [Multimodal EmotionLines Dataset (MELD)](https://github.com/SenticNet/MELD) - Multimodal EmotionLines Dataset (MELD) has been created by enhancing and extending EmotionLines dataset. MELD contains the same dialogue instances available in EmotionLines, but it also encompasses audio and visual modality along with text. MELD has more than 1400 dialogues and 13000 utterances from Friends TV series. Each utterance in a dialogue has been labeled with— Anger, Disgust, Sadness, Joy, Neutral, Surprise and Fear. 
* [Multilingual Spoken Words Corpus (MSWC)](https://mlcommons.org/datasets/multilingual-spoken-words/) - 50-language spoken keyword corpus from MLCommons for keyword spotting and spoken term search.
* [MuSe-CAR](https://zenodo.org/record/4134758) - 40 hours, 6,000+ recordings of 25,000+ sentences by 70+ English speakers (15 GB).
* [NISQA Speech Quality Corpus](https://github.com/gabrielmittag/NISQA/wiki/NISQA-Corpus) - includes 14k speech samples with simulated (codecs, packet-loss, background noise) and live (mobile phone, Zoom, Skype, WhatsApp) voice call degradation conditions. Each file is labelled with subjective ratings of the overall quality and the quality dimensions Noisiness, Coloration, Discontinuity, and Loudness. 
* [NeuroVoz](https://zenodo.org/records/13647600) - Castilian Spanish Parkinsonian speech corpus with clinical/control speakers and multiple speech tasks.
* [Nonverbal Vocalization Dataset](https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset) - Human nonverbal vocalization dataset for acoustic event and paralinguistic modeling.
* [Noisy Dataset](https://datashare.is.ed.ac.uk/handle/10283/2791)- Clean and noisy parallel speech database. The database was designed to train and test speech enhancement methods that operate at 48kHz. Also known as VBD, Voice Bank + DEMAND. Speech samples from VCTK dataset.
* [OGVC](https://sites.google.com/site/ogcorpus/home/en) - 9114 spontaneous utterances and 2656 acted utterances by 4 professional actors (two male and two female); 9 emotional states: fear, surprise, sadness, disgust, anger, anticipation, joy, acceptance and the neutral state.
* [OpenSLR](https://openslr.org) - Many audio datasets (>109) published for speech recognition purposes. 
* [Parkinson's speech dataset](https://archive.ics.uci.edu/dataset/301/parkinson+speech+dataset+with+multiple+types+of+sound+recordings) - The training data belongs to 20 Parkinson’s Disease (PD) patients and 20 healthy subjects. From all subjects, multiple types of sound recordings (26) are taken for this 20 MB set.
* [Parent-Child Vocal Interaction Dataset](https://github.com/deeplyinc/Parent-Child-Vocal-Interaction-Dataset) - Parent-child conversational vocal interaction recordings for speech and interaction analysis.
* [Parrot Radiology ASR EN](https://huggingface.co/datasets/ysdede/parrot-radiology-asr-en) - Synthetic English radiology speech corpus with paired transcripts for domain ASR.
* [People's Speech](https://mlcommons.org/en/peoples-speech/) - Large-scale speech corpus released by MLCommons for open ASR training.
* [Persian Consonant Vowel Combination (PCVC) Speech Dataset](https://github.com/S-Malek/PCVC) - The Persian Consonant Vowel Combination (PCVC) Speech Dataset is a Modern Persian speech corpus for speech recognition and also speaker recognition. This dataset contains 23 Persian consonants and 6 vowels. The sound samples are all possible combinations of vowels and consonants (138 samples for each speaker) with a length of 30000 data samples.
* [RECOLA](https://qualinet.github.io/databases/audiovisual/recola/) - 3.8 hours of recordings by 46 participants; negative and positive sentiment (valence and arousal).
* [The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://zenodo.org/record/1188976#.XrC7a5NKjOR) - The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains 7356 files (total size: 24.8 GB). The database contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions.
* [sample_voice_data](https://github.com/jim-schwoebel/sample_voice_data) - 52 audio files per class (males and females) for testing purposes.
* [SAVEE Dataset](http://kahlan.eps.surrey.ac.uk/savee/) -  4 male actors in 7 different emotions, 480 British English utterances in total.
* [SEMAINE](https://doi.org/10.1109/T-AFFC.2011.15) - 95 dyadic conversations from 21 subjects. Each subject converses with another playing one of four characters with emotions; 5 FeelTrace annotations: activation, valence, dominance, power, intensity.
* [SEP-28k](https://www.kaggle.com/datasets/ikrbasak/sep-28k) - Stuttering events dataset with ~28k annotated 3-second podcast clips plus FluencyBank subset metadata.
* [SER Datasets](https://github.com/SuperKogito/SER-datasets) - A collection of datasets for the purpose of emotion recognition/detection in speech.
* [SEWA](https://sewaproject.eu/resources) - more than 2000 minutes of audio-visual data of 398 people (201 male and 197 female) coming from 6 cultures; emotions are characterized using valence and arousal.
* [ShEMO](https://github.com/mansourehk/ShEMO) - 3000 semi-natural utterances, equivalent to 3 hours and 25 minutes of speech data from online radio plays by 87 native-Persian speakers; 6 emotions: anger, fear, happiness, sadness, neutral and surprise.
* [SparseLibriMix](https://github.com/popcornell/SparseLibriMix) - An open source dataset for source separation in noisy environments and with variable overlap-ratio. Due to insufficient noise material this is a test-set-only version.
* [SPGISpeech](https://datasets.kensho.com/datasets/spgispeech) - 5,000-hour real-world and anonymized English speech corpus for ASR.
* [Speech Accent Archive](https://www.kaggle.com/datasets/rtatman/speech-accent-archive) - For various accent detection tasks.
* [Speech Commands Dataset](https://research.google/blog/launching-the-speech-commands-dataset/) - The dataset (1.4 GB) has 65,000 one-second long utterances of 30 short words, by thousands of different people, contributed by members of the public through the AIY website.
* [Spoken Commands dataset](https://github.com/JohannesBuchner/spoken-command-recognition) - A large database of free audio samples (10M words), a test bed for voice activity detection algorithms and for recognition of syllables (single-word commands). 3 speakers, 1,500 recordings (50 of each digit per speaker), English pronunciations. This is a really small set- about 10 MB in size.
* [Spoken Wikipeida Corpora](https://nats.gitlab.io/swc/) - 38 GB in size available in both audio and without audio format.
* [Tatoeba](https://tatoeba.org/eng/downloads) - Tatoeba is a large database of sentences, translations, and spoken audio for use in language learning. This download contains spoken English recorded by their community.
* [Ted-LIUM](https://www.openslr.org/51/) - The TED-LIUM corpus was made from audio talks and their transcriptions available on the TED website (noncommercial).
* [TESS](https://tspace.library.utoronto.ca/handle/1807/24487) - 2800 recording by 2 actresses; 7 emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
* [Thorsten dataset](https://github.com/thorstenMueller/deep-learning-german-tts/) - German language dataset, 22,668 recorded phrases, 23 hours of audio, phrase length 52 characters on average.
* [TIMIT dataset](https://catalog.ldc.upenn.edu/LDC93S1) - TIMIT contains broadband recordings of 630 speakers of eight major dialects of American English, each reading ten phonetically rich sentences. It includes time-aligned orthographic, phonetic and word transcriptions as well as a 16-bit, 16 kHz speech waveform file for each utterance (have to pay).
* [URDU-Dataset](https://github.com/siddiquelatif/urdu-dataset) - 400 utterances by 38 speakers (27 male and 11 female); 4 emotions: angry, happy, neutral, and sad.
* [VCTK dataset](https://datashare.is.ed.ac.uk/handle/10283/3443) - 110 English speakers with various accents; each speaker reads out about 400 sentences. Samples are mostly 2–6 s long, at 48 kHz 16 bits, for a total dataset size of ~10 GiB.
* [VCTK-2Mix](https://github.com/JorisCos/VCTK-2Mix) - VCTK-2Mix is an open source dataset for source separation in noisy environments. It is derived from VCTK signals and WHAM noise. It is meant as a test set. It will also enable cross-dataset experiments.
* [VIVAE](https://zenodo.org/record/4066235) - non-speech, 1085 audio file by ~12 speakers; non-speech 6 emotions: achievement, anger, fear, pain, pleasure, and surprise with 3 emotional intensities (low, moderate, strong, peak).
* [VocalSound](https://github.com/YuanGongND/vocalsound) - 21,024 recordings of human non-speech vocal sounds (laughs, coughs, sneezes, etc.) with rich metadata.
* [Voice Gender Detection](https://github.com/jim-schwoebel/voice_gender_detection) - GitHub repo for Voice gender detection using the VoxCeleb dataset (7000+ unique speakers and utterances, 3683 males / 2312 females).
* [VOiCES Dataset](https://iqtlabs.github.io/voices/) - The Voices Obscured in Complex Environmental Settings (VOiCES) corpus is a creative commons speech dataset targeting acoustically challenging and reverberant environments with robust labels and truth data for transcription, denoising, and speaker identification.
* [VoxCeleb](https://github.com/andabi/voice-vector) - VoxCeleb is a large-scale speaker identification dataset. It contains around 100,000 utterances by 1,251 celebrities, extracted from You Tube videos. The data is mostly gender balanced (males comprise of 55%). The celebrities span a diverse range of accents, professions, and age. There is no overlap between the development and test sets. It’s an intriguing use case for isolating and identifying which superstar the voice belongs to.
* [VoxForge](https://www.voxforge.org/home/downloads) - VoxForge was set up to collect transcribed speech for use with Free and Open Source Speech Recognition Engines.
* [VoxPopuli](https://github.com/facebookresearch/voxpopuli) - VoxPopuli provides 100K hours of unlabelled speech data for 23 languages, 1.8K hours of transcribed speech data for 16 languages, and 17.3K hours of speech-to-speech interpretation data for 16x15 directions.
* [WHAM! and WHAMR!](https://arxiv.org/abs/1910.10279) - The WSJ0 Hipster Ambient Mixtures (WHAM!) dataset pairs each two-speaker mixture in the wsj0-2mix dataset with a unique noise background scene. WHAMR! is an extension to WHAM! that adds artificial reverberation to the speech signals in addition to the background noise. The noise audio was collected at various urban locations throughout the San Francisco Bay Area in late 2018. The environments primarily consist of restaurants, cafes, bars, and parks. Size of WHAM! dataset: 17.65 GB unzipping to 35 GB.
* [Zero Resource Speech Challenge](https://github.com/bootphon/zerospeech2017) - The ultimate goal of the Zero Resource Speech Challenge is to construct a system that learns an end-to-end Spoken Dialog (SD) system, in an unknown language, from scratch, using only information available to a language learning infant. “Zero resource” refers to zero linguistic expertise (e.g., orthographic/linguistic transcriptions), not zero information besides audio (visual, limited human feedback, etc). The fact that 4-year-olds spontaneously learn a language without supervision from language experts show that this goal is theoretically reachable.

</details>

<details open>
<summary><strong>Audio events and music</strong></summary>

* [AudioSet](https://research.google.com/audioset/) - An expanding ontology of 632 audio event classes and a collection of 2,084,320 human-labeled 10-second sound clips drawn from YouTube videos. Easily download AudioSet [here](https://github.com/jim-schwoebel/download_audioset).
* [Bird audio detection challenge](http://machine-listening.eecs.qmul.ac.uk/bird-audio-detection-challenge/) -  This challenge contained new datasets (5.4 GB) collected in real live bio-acoustics monitoring projects, and an objective, standardized evaluation framework.
* [Environmental audio dataset](https://toni-heittola.github.io/datasets) - Audio data collection and manual data annotation both are tedious processes, and lack of proper development dataset limits fast development in the environmental audio research.
* [Free Music Archive](https://github.com/mdeff/fma) - FMA is a dataset for music analysis. 1000 GB in size.
* [Freesound dataset](https://www.kaggle.com/c/freesound-audio-tagging-2019/data) - 678,511 candidate annotations that express the potential presence of sound sources in audio clips. See https://annotator.freesound.org/ and https://annotator.freesound.org/fsd/explore/ for more information. 
* [Karoldvl-ESC](https://github.com/karoldvl/ESC-50) - The ESC-50 dataset is a labeled collection of 2000 environmental audio recordings suitable for benchmarking methods of environmental sound classification.
* [ISMIR Datasets List](https://www.ismir.net/resources/datasets/) - Community-maintained index of music information retrieval datasets.
* [Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/) - The Million Song Dataset is a freely-available collection of audio features and meta-data for a million contemporary popular music tracks. 280 GB in size.
* [MUSDB18](https://github.com/sigsep/sigsep-mus-db) - Multi-track music dataset for music source separation. 150 tracks (22 Gb).
* [Public domain sounds](https://pdsounds.tuxfamily.org/) - Good for wake word detection; a wide array of sounds that can be used for object detection research (524 MB - 635 SOUNDS - Open for public use). 
* [RSC Sounds](https://github.com/2003scape/rsc-sounds) - RSC sounds from RuneScape Classic (8-bit, u-law encoded, 8000 Hz pcm samples).
* [Urban Sound Dataset](https://urbansounddataset.weebly.com/) - two datasets and a taxonomy for urban sound research.

</details>

## Upstream provenance
* Original repository (source inspiration): [jim-schwoebel/voice_datasets](https://github.com/jim-schwoebel/voice_datasets).
* Maintained fork (active updates and curation): [chikingsley/voice_datasets](https://github.com/chikingsley/voice_datasets).
* This fork keeps attribution to upstream while maintaining an updated catalog and contribution workflow.

## Learn more
Any feedback this repository is greatly appreciated. 

* Suggest a new dataset to add in [Issues](https://github.com/chikingsley/voice_datasets/issues).
* Read [CONTRIBUTING.md](./CONTRIBUTING.md) for curation and validation guidelines.
* If you want to learn more about voice computing, check out [Voice Computing in Python](https://github.com/jim-schwoebel/voicebook) book.
* If you are looking for a framework to start building machine learning models in voice computing, check out [Allie](https://github.com/jim-schwoebel/allie).
* Open a pull request if you have vetted additions or dead-link fixes.
