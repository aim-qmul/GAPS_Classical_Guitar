---
layout: default
---

## Introduction
Welcome to the website for the ISMIR 2024 paper [GAPS: A Large and Diverse Classical Guitar Dataset and Benchmark Transcription Model](https://arxiv.org/abs/2408.08653). This work was carried out by **Xavier Riley**, **Zixun Nicolas Guo**, **Drew Edwards** and their supervisor **Simon Dixon** on the [AIM programme](https://www.aim.qmul.ac.uk/) at the Center for Digital Music, QMUL. 

GAPS is the largest dataset of real guitar audio (as of Nov 2024), containing 14 hours of freely available audio-score aligned pairs, high-resolution note-level MIDI alignments and performance videos, recorded in diverse conditions by over 200 performers. This dataset has applications to various MIR tasks, including automatic music transcription, score following, performance analysis, generative music modelling and the study of expressive performance timing.

## Preview of Data
#### Audio File:
<audio controls>
    <source src="{{ site.baseurl }}/assets/media/-Sswc.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

#### MIDI File:
<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.5.0"></script>
<midi-player
  src="{{ site.baseurl }}/assets/media/-Sswc-fine-aligned.mid"
  sound-font visualizer="#myVisualizer">
</midi-player>
<midi-visualizer type="piano-roll" id="myVisualizer"></midi-visualizer>


## Download Links
- [Download Dataset](ZENODO)

## How to Use
You can find the dataset usage information on our [Zenodo Page](#).

## Cite Us
<style>
  pre, code {
    max-width: 800px; /* Set a suitable width */
    padding: 1px; /* Reduced padding to make it tighter */
    margin: 1px 0; /* Reduced margin to minimize extra space */
    border: 1px solid #ccc; /* Keeps a thin border */
    background-color: #f8f8ff; /* Light background color */
    overflow-x: auto; /* Ensures horizontal scroll if needed */
  }
</style>
  <pre>
  <code>
  @inproceedings{GAPS,
  author       = {Xavier Riley and Zixun Guo and Drew Edwards and Simon Dixon},
  title        = {GAPS: A Large and Diverse Classical Guitar Dataset and Benchmark Transcription Model},
  booktitle    = {Proceedings of the 25th International Society for Music Information Retrieval Conference {(ISMIR} 2024), San Francisco, USA, November 10, 2024},
  year         = {2024}}
  </code>
  </pre>

## License
The GAPS dataset contains copyright material and is shared with researchers under the following conditions:
  - GAPS may only be used by the individual signing below and by members of the research group or organisation of this individual. This permission is not transferable.
  - GAPS may be used only for non-commercial research purposes.
  - GAPS (or data enabling the its reproduction) may not be sold, leased, published or distributed to any third party without written permission from the GAPS administrator.
  - When research results obtained using GAPS are publicly released (in the form of reports, publications, or derivative software), clear indication of the use of GAPS shall be given, usually in the form of a citation. 
  - Queen Mary University of London shall not be held liable for any errors in the content of GAPS nor damage arising from the use of GAPS.
The GAPS administrator may update these conditions of use at any time.

---