# Data for the DIALECT-COPA unshared task of dialectal causal common-sense reasoning

This repository contains the training and validation data (val.jsonl) for the [DIALECT-COPA unshared task](https://sites.google.com/view/vardial-2024/shared-tasks/dialect-copa?authuser=0).

Each folder consists of training (400 instances, train.jsonl) and validation (100 instances, val.jsonl) data from the original [COPA dataset](https://people.ict.usc.edu/~gordon/copa.html), human-translated in the specific language or dialect. Languages that (also) use the Cyrillic alphabet have additional files transliterated into the Latin alphabet (train.trans.jsonl and val.trans.jsonl).

Bear in mind that each dialect is related primarily to the corresponding standard language, but that standard languages are very much related as well.

- copa-sl - Slovenian language
- copa-sl-cer - The Cerkno dialect of the Slovenian language
- copa-hr - Croatian language
- copa-sr - Serbian language
- copa-sr-tor - The Torlak dialect of the Serbian, Macedonian, Bulgarian languages
- copa-mk - Macedonian language

In the testing phase of the unshared task, test data from the copa-sl-cer and the copa-sr-tor datasets will be shared with the participants, along with the test data of the copa-hr-ckm dataset, the surprise dialect of the unshared task - the Chakavian dialect of the Croatian language.
