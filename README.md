


### Cozmo Affect Data

This is the data we collected and used in our [RSS 2019 paper](http://www.roboticsproceedings.org/rss15/p41.html).

The `affect_data.csv` file has the following columns:

- file_name
- embed_code
- video_title
- description
- interest - desire
- valence

The `file_name` refers to the string name of the animation, which functions as a unique identifier (e.g., `anim_play_requestplay_level2_01`). The `embed_code` is the YouTube embed code for that particular animation (e.g., the embed_code for `nMbYAONAots` can be viewed on YouTube as follows: https://www.youtube.com/watch?v=nMbYAONAots). The `description` and `interest` through `desire` columns (16 possible affects) were obtained using Mechanical Turk. We had turkers watch the YouTube videos and label them for affect and also give a description. Note that each animation should have at least two descriptions and affect labels (i.e., two rows). 

In addition to the .csv file, you can also download the corresponding [wav audio](https://drive.google.com/file/d/1pfR1Q0CnvCnI2sRGxeKSeeFxA73J5ech/view?usp=sharing) where the names of the wav files match the `file_name`. 

We are also making the faces available. Unforatunately, we can't programatically observe Cozmo's face through the API, so we used some simple computer vision processing to derive faces from the videos. That data can be downloaded [here](https://drive.google.com/file/d/1p9cXTDeQSIorQwbJzYlRgNahClJQgJ1U/view?usp=sharing).

If you use this data, please cite:

```
  
@INPROCEEDINGS{Kennington-RSS-19, 
    AUTHOR    = {David McNeill AND Casey Kennington}, 
    TITLE     = {Predicting Human Interpretations of Affect and Valence in a Social Robot}, 
    BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
    YEAR      = {2019}, 
    ADDRESS   = {FreiburgimBreisgau, Germany}, 
    MONTH     = {June}, 
    DOI       = {10.15607/RSS.2019.XV.041} 
} 
```




