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
'''
@inproceedings{Meng2023FOLLOWUPQGTI,
  title={FOLLOWUPQG: Towards Information-Seeking Follow-up Question Generation},
  author={Yan Meng and Liangming Pan and Yixin Cao and Min-Yen Kan},
  year={2023},
  url={https://api.semanticscholar.org/CorpusID:261681892}
}
'''

