# FollowupQG Dataset


### Introduction
FollowupQG is a dataset of over 3K real-world ***(initial question, answer, follow-up question)*** tuples collected from a Reddit forum providing layman-friendly explanations for open-ended questions. In contrast to existing datasets, questions in FollowupQG use more diverse pragmatic strategies to seek information, and they also show higher-order cognitive skills (such as applying and relating).  

###  Data Samples
```
{
    "id": 22,
    "question": "How has space dust (oversimplified) formed both planets as well as dust clouds?",
    "answer": "For a dust cloud to collapse it needs to have a certain density.  If dust is spread out too much the gravity is too weak to pull it together. (It's weaker than the kinetic energy of the dust particles). Compare this to a planet orbiting. It doesn't fall into the star because gravity and it's centrifugal force cancel each other out.  But at a certain point there is a runaway condition, it gets together a little, wich increases density and gravity becomes stronger causing this effect to quickly escalate. At that point a star system forms.",
    "follow-up": "Could you theoretically throw a big rock into a dust cloud and eventually have the gravity of the rock pull in the dust? Or is the dust cloud simply too spread out to be affected by gravity on the scale needed to produce any effects?",
    "relation": "Strongly Related"
  }
```

```
{
    "id": 12,
    "question": "Why is Pluto not a planet?",
    "answer": "Because Pluto is too small and there are several other similarly sized objects (like Eris and Ceres) that are not elevated to \"Planet\" so a new group was created to describe these small but significant objects in Solar orbit.",
    "follow-up": "Ok, If I grant you the premise that Pluto isn't a planet, what is this new group called?",
    "relation": "Slightly Related"
  }
```




### Data Split

* Training Size: 2790
* Validation Size: 500
* Test Size: 500

### Cite
```
@inproceedings{meng-etal-2023-followupqg,
    title = "{F}ollowup{QG}: Towards information-seeking follow-up question generation",
    author = "Meng, Yan  and
      Pan, Liangming  and
      Cao, Yixin  and
      Kan, Min-Yen",
    editor = "Park, Jong C.  and
      Arase, Yuki  and
      Hu, Baotian  and
      Lu, Wei  and
      Wijaya, Derry  and
      Purwarianti, Ayu  and
      Krisnadhi, Adila Alfa",
    booktitle = "Proceedings of the 13th International Joint Conference on Natural Language Processing and the 3rd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = nov,
    year = "2023",
    address = "Nusa Dua, Bali",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.ijcnlp-main.17",
    doi = "10.18653/v1/2023.ijcnlp-main.17",
    pages = "252--271",
}

```


