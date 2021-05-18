# Entity Extraction using BERT

## About the Dataset
[Link to Dataset](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)

### Context
Annotated Corpus for Named Entity Recognition using GMB(Groningen Meaning Bank) corpus for entity classification with enhanced and popular features by Natural Language Processing applied to the data set.

### Content
This is the extract from GMB corpus which is tagged, annotated and built specifically to train the classifier to predict named entities such as name, location, etc.

*Number of tagged entities:*
```
'O': 1146068', geo-nam': 58388, 'org-nam': 48034, 'per-nam': 23790, 'gpe-nam': 20680, 'tim-dat': 12786, 'tim-dow': 11404, 'per-tit': 9800, 'per-fam': 8152, 'tim-yoc': 5290, 'tim-moy': 4262, 'per-giv': 2413, 'tim-clo': 891, 'art-nam': 866, 'eve-nam': 602, 'nat-nam': 300, 'tim-nam': 146, 'eve-ord': 107, 'per-ini': 60, 'org-leg': 60, 'per-ord': 38, 'tim-dom': 10, 'per-mid': 1, 'art-add': 1
```

*Essential info about entities:*
- geo = Geographical Entity
- org = Organization
- per = Person
- gpe = Geopolitical Entity
- tim = Time indicator
- art = Artifact
- eve = Event
- nat = Natural Phenomenon

Total Words Count = 1354149  
Target Data Column: "tag"

## References
- [Building an entity extraction model using BERT](https://www.youtube.com/watch?v=MqQ7rqRllIc&t=2294s)
- [HuggingFace Transformers Tokenizer](https://huggingface.co/transformers/v2.11.0/main_classes/tokenizer.html)
- [HuggingFace Transformers Glossary](https://huggingface.co/transformers/glossary.html)
