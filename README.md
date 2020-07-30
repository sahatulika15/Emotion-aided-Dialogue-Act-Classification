# Emotion-aided-Dialogue-Act-Classification

## This is the readme file that contains the information about the dataset introduced in the following paper

**Paper Name:-** Emotion aided Dialogue Act Classification for Task-Independent Conversations in a Multi-Modal Framework
>Introduction: Dialogue Act Classification (DAC) gives a significant insight for understanding the communicative intention of the user. Numerous Machine Learning (ML) and Deep Learning (DL) approaches have been proposed over the years in these regards for task-oriented/independent conversations in the form of texts. However, the affect of emotional state in determining the Dialogue Acts (DAs) has not been studied in depth in a multi-modal framework involving text, audio and visual features. Conversations are intrinsically determined and regulated by direct, exquisite and subtle emotions. The emotional state of a speaker has a considerable affect on its intentional or its pragmatic content.
Methods: This paper thoroughly investigates the role of emotions in automatic identification of the DAs in task-independent conversations in a multi-modal framework (specifically audio and texts). A DL based multi-tasking network for DAC and Emotion Recognition (ER) has been developed incorporating attention to facilitate the fusion of different modalities. An open source, benchmarked ER multi-modal data-set IEMOCAP has been manually annotated for its corresponding DAs to make it suitable for multi-task learning and further advance the research in multi-modal DAC. 
Results:  The proposed multi-task framework attains an improvement of 2.5\% against its single task DAC counterpart for manually annotated IEMOCAP data-set.
Conclusion: Results as compared to several baselines establish the efficacy of the proposed approach and the importance of incorporating emotion while identifying the DAs.

* **Authors:** Tulika Saha, Dhawal Gupta, Sriparna Saha and Pushpak Bhattacharyya
* **Affiliation:** Indian Institute of Technology Patna, India
* **Corresponding Author:** [Tulika Saha](sahatulika15@gmail.com / tulika.pcs16@iitp.ac.in)
* **Accepted(January, 2020):**  [Cognitive Computation Journal](https://link.springer.com/article/10.1007/s12559-019-09704-5)

If you consider this dataset useful, please cite it as
```bash
@article{saha2020emotion,
  title={Emotion Aided Dialogue Act Classification for Task-Independent Conversations in a Multi-modal Framework},
  author={Saha, Tulika and Gupta, Dhawal and Saha, Sriparna and Bhattacharyya, Pushpak},
  journal={Cognitive Computation},
  pages={1--13},
  year={2020},
  publisher={Springer}
}
```

# Description

1. The dataset is curated by collecting conversations from open sourced dataset IEMOCAP.
2. IEMOCAP has pre-annotated emotion labels.
3. The 12 DA annotated catefories are "Greeting (g)", "Question (q)", "Answer (ans)", "Statement-Opinion (o)", "Statement-Non-Opinion (s)", "Apology (ap)", "Command (c)", "Agreement (ag)", "Disagreement (dag)", "Acknowledge (a)", "Backchannel (b)" and "Others (oth)".
4. The videos of the transcript can be downloaded from the source dataset : https://sail.usc.edu/iemocap/iemocap_release.htm

# Contact

For any queries, feel free to contact the corresponding author : Tulika Saha (sahatulika15@gmail.com)
