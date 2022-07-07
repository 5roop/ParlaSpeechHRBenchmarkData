# ParlaSpeechHRBenchmarkData
Data used for the paper 'The ParlaSpeech-HR benchmark for speaker profiling in Croatian'

## Age dataset:

[Dataset](age.jsonl) has 3 attributes:

* `file`: audio file, see ParlaSpeech-HR dataset
* `split`: which split the instance belongs to (train, dev, test)
* `Speaker_age_group`: either `young` or `old`, based on the median age of speakers

## Gender dataset:

[Dataset](gender.jsonl) has 3 attributes:

* `file`: audio file, see [ParlaSpeech-HR dataset](https://www.clarin.si/repository/xmlui/handle/11356/1494)
* `split`: which split the instance belongs to (train, dev, test)
* `Speaker_gender`: either `M` or `F`.

## Party status dataset:

[Dataset](party_status.jsonl) has 3 attributes:

* `file`: audio file, see [ParlaSpeech-HR dataset](https://www.clarin.si/repository/xmlui/handle/11356/1494)
* `split`: which split the instance belongs to (train, dev, test)
* `Party_status`: either `Coalition` or `Opposition`

## Speaker_id dataset:

[Dataset](speaker_id.jsonl) has 3 attributes:

* `file`: audio file, see [ParlaSpeech-HR dataset](https://www.clarin.si/repository/xmlui/handle/11356/1494)
* `split`: which split the instance belongs to (train, dev, test)
* `Speaker_name`: name of the speaker.