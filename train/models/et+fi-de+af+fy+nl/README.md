# opus-2019-12-04.zip

* dataset: opus
* model: transformer
* pre-processing: normalization + tokenization + BPE
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2019-12-04.zip](https://object.pouta.csc.fi/OPUS-MT-models/et+fi-de+af+fy+nl/opus-2019-12-04.zip)
* test set translations: [opus-2019-12-04.test.txt](https://object.pouta.csc.fi/OPUS-MT-models/et+fi-de+af+fy+nl/opus-2019-12-04.test.txt)
* test set scores: [opus-2019-12-04.eval.txt](https://object.pouta.csc.fi/OPUS-MT-models/et+fi-de+af+fy+nl/opus-2019-12-04.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba.et.nl 	| 43.9 	| 0.623 |
