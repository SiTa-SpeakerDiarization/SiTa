# SiTa: A Speaker Diarization Dataset

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

**SiTa** is a diarization dataset featuring multispeaker audio clips in the Sinhala and Tamil languages. The dataset is curated to support research in speaker diarization and related audio processing tasks. It includes high-quality annotations for accurate evaluation.

📜 **Paper :** [SiTa - Sinhala and Tamil Speaker Diarization Dataset in the Wild](https://aclanthology.org/2025.chipsal-1.8/)

🌐 **Website :** [sita-speakerdiarization.github.io](https://sita-speakerdiarization.github.io/)

## Dataset Overview

The SiTa dataset has two subsets, one for Sinhala and another for Tamil. It provides audio clips in WAV format accompanied by Rich Transcription Time Marked (RTTM) files containing speaker diarization annotations. The dataset contains 10 hours of Sinhala audio and 2 hours of Tamil audio.

### List of YouTube Videos

The given Excel sheet provides the youtube links from which the audio clips were extracted as well as start time end time details.
Full catalog of the dataset sources can be found [here](https://github.com/SiTa-SpeakerDiarization/SiTa/blob/main/SiTa%20Audio%20Source%20Info.xlsx)

### Audio Files

- **SiTa Dataset:**
- Audio files for the Sinhala and Tamil dataset can be downloaded [here](https://rtuthaya.staff.uom.lk/contact-for-resources).
- Please request access if the dataset is not available to the public. We are currently working on arranging alternative hosting for the dataset.

### RTTM Annotations

Annotations provided in RTTM format are organized within the `manual_sorted_rttm` folders. These annotations ensure precise time-stamped speaker labels for each audio clip.

## Updates and Additional Information

For the latest updates and detailed information about SiTa, please contact:

- rtuthaya@cse.mrt.ac.lk
- thulasithan.20@cse.mrt.ac.lk
- kasuni.20@cse.mrt.ac.lk
- shamila.20@cse.mrt.ac.lk

## Citation

If you use the **SiTa - Sinhala and Tamil Speaker Diarization Dataset in the Wild** in your research, please cite our work from <a href="https://aclanthology.org/2025.chipsal-1.8/">ACL anthology</a>:

```bibtex
@inproceedings{thayasivam-etal-2025-sita,
    title = "{S}i{T}a - {S}inhala and {T}amil Speaker Diarization Dataset in the Wild",
    author = "Thayasivam, Uthayasanker  and
      Gnanenthiram, Thulasithan  and
      Jeewantha, Shamila  and
      Jayawickrama, Upeksha",
    editor = "Sarveswaran, Kengatharaiyer  and
      Vaidya, Ashwini  and
      Krishna Bal, Bal  and
      Shams, Sana  and
      Thapa, Surendrabikram",
    booktitle = "Proceedings of the First Workshop on Challenges in Processing South Asian Languages (CHiPSAL 2025)",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2025.chipsal-1.8/",
    pages = "83--92",
    abstract = "The dynamic field of speaker diarization continues to present significant challenges, despite notable advancements in recent years and the rising focus on complex acoustic scenarios emphasizes the importance of sustained research efforts in this area. While speech resources for speaker diarization are expanding rapidly, aided by semi-automated techniques, many existing datasets remain outdated and lack authentic real-world conversational data. This challenge is particularly acute for low-resource South Asian languages, due to limited public media data and reduced research efforts. Sinhala and Tamil are two such languages with limited speaker diarization datasets. To address this gap, we introduce a new speaker diarization dataset for these languages and evaluate multiple existing models to assess their performance. This work provides essential resources, a novel dataset and valuable insights from model benchmarks to advance speaker diarization for low-resource languages, particularly Sinhala and Tamil."
}
```

## License

This work is licensed under
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
