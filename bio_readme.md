## Data Format Descprition
The datasets are formatted in JSON and organized as follows:

```
[{
	"id": "ID of sentence 1.",
	"sentence": "Body of the sentence 1.",
	"triples": [{
		"uid": "ID of the first triplet of sentence 1.",
		"target_tags": "The aspect phrase with BIO scheme.",
		"opinion_tags": "The corresponding one opinion phrase for the aspect phrase with BIO scheme.",
		"sentiment": "The corresponding sentiment polarity of the triplet."
	},{
        The second triplet of sentence 1.
        ...
    }]
}, {
	Sentence 2.
    ...
}]
```

So each part of 'triples' section contains information about one selected triplet (Aspect phrase - Opinion phrase - Sentiment).
