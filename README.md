# CAPSTONE_PROJECT
# Capstone Project - Real-Time Accent Translation System

**Problem Statement Number**: [PSCS95](#title)  
**Organization**: HARMAN  
**Category**: Software  
**Difficulty Level**: Complicated


- [Title](#title)
- [Objectives](#objectives)
- [Methodology](#methodology)

---

## <a name="title"></a> Title
**Real-Time Accent Translation System for Conference Calls**

---

## <a name="objectives"></a> Objectives
- **Primary Objective**:  
  Develop a real-time accent translation system that improves communication during conference calls by translating accents.

- **Secondary Objectives**:
  - Implement Speech-to-Text (STT) conversion.
  - Modify the text to match the recipient's accent using phonetic processing.
  - Convert processed text into speech using Text-to-Speech (TTS).
  - Ensure real-time streaming for live audio.

---


## <a name="methodology"></a> Methodology
The methodology is broken down into multiple stages to handle the real-time translation of accents:

- Speech Recognition (STT):
  Tools: Google Speech-to-Text API
  Convert spoken words into text in real-time.

- Language Translation:
  Tools: Google translation API
  For efficient text translation between source and target language.

- Text-to-Speech (TTS):
  Tools: Google TTS
  Convert the processed text back into speech with the desired accent.

- Efficient File Handling:
  Store temporary audio files dynamically with UUID-based unique naming.

---

