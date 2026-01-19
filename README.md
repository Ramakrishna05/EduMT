## EduMT

This repository contains the Hindi-Bengali educational domain parallel corpus created as part of the work titled "EduMT: Developing Machine Translation System for Educational Content in Indian Languages".

### Data
The folder 'Data' contains four sub-folders:
- Subtitles: Synthetic data extracted from the YouTube video lecture subtitles of size 439,914 sentences.
- Post-Edited: The post-edited synthetic data of size 40,236 sentences.
- Transcripts: Synthetic data generated from crawling lecture transcripts and translating them into Hindi and Bengali using Google Translate, of size 508,339 sentences.
- Test: Manually created test sets used in our experiments of size 2,630 sentences.

**Note:** Due to the file size limitations, Opus and Synthetic data are uploaded externally and can be accessed at: [GDrive Link](https://drive.google.com/drive/folders/1e4PeUZpLFj4az2JDpQZA37T5CXcbaJMi?usp=sharing). Post-edited and Test datasets are accessible from the respective folders. Subtitles and Transcripts data may contain noisy sentences. Kindly preprocess them before using them to train the models.

### Citation
Please kindly cite the following paper if you have used our dataset:

```
@inproceedings{appicharla-etal-2021-edumt,
    title = "EduMT: Developing Machine Translation System for Educational Content in Indian Languages",
    author = "Appicharla, Ramakrishna  and
      Ekbal, Asif  and
      Bhattacharyya, Pushpak",
    editor = "Bandyopadhyay, Sivaji  and
      Devi, Sobha Lalitha  and
      Bhattacharyya, Pushpak",
    booktitle = "Proceedings of the 18th International Conference on Natural Language Processing (ICON)",
    month = dec,
    year = "2021",
    address = "National Institute of Technology Silchar, Silchar, India",
    publisher = "NLP Association of India (NLPAI)",
    url = "https://aclanthology.org/2021.icon-main.6/",
    pages = "35--43",
}
```
