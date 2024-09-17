# xlmr-emotion
This is the pre-trained language model (PLM) that was used to analyse the sentiment in Greek political speech, by focusing on the most frequently occurring emotion in electoral data, the emotion of "disgust". 

The study shows that emotion classification is generally tough, but high accuracy can be achieved for that particular emotion. An XLM-R model was fine-tuned and then used to classify political records of the Greek Parliament Corpus from 1989 to 2020. Using the predictions, we studied the points in time when this emotion was frequently occurring and we ranked the Greek political parties based on their estimated score. 

We then devised an algorithm to investigate the emotional context shift of words that describe specific conditions and that can be used to stigmatise. Given that early detection of such word usage is essential for policy-making, we report two words we found being increasingly used in a negative emotional context, and one that is likely to be carrying stigma, in the studied parliamentary records.

---

The weights of the XLM-R model that was fine-tuned for emotion classification on the data of [SemEval 2018 Task 1](https://aclanthology.org/S18-1001/), is available in this repository. A notebook loading is also provided. 

---

To cite this work, please use:
```
@inproceedings{lislevand-etal-2024-estimating,
    title = "Estimating the Emotion of Disgust in {G}reek Parliament Records",
    author = "Lislevand, Vanessa  and
      Pavlopoulos, John  and
      Louridas, Panos  and
      Dritsa, Konstantina",
    editor = {Chung, Yi-Ling  and
      Talat, Zeerak  and
      Nozza, Debora  and
      Plaza-del-Arco, Flor Miriam  and
      R{\"o}ttger, Paul  and
      Mostafazadeh Davani, Aida  and
      Calabrese, Agostina},
    booktitle = "Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.woah-1.9",
    doi = "10.18653/v1/2024.woah-1.9",
    pages = "118--135"
}
```
