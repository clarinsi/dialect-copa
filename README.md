# Data for the DIALECT-COPA shared task of dialectal causal commonsense reasoning

This repository contains the training and validation data for the [DIALECT-COPA shared task](https://sites.google.com/view/vardial-2024/shared-tasks/dialect-copa?authuser=0).

Each folder consists of training (400 instances, train.jsonl) and validation (100 instances, val.jsonl) data from the original [COPA dataset](https://people.ict.usc.edu/~gordon/copa.html), human-translated in the specific language or dialect. Languages that (also) use the Cyrillic alphabet have additional files transliterated into the Latin alphabet (train.trans.jsonl and val.trans.jsonl).

Bear in mind that each dialect is related primarily to the corresponding standard language, but that standard languages are very much related between themselves as well.

- [copa-sl](copa-sl/) - Slovenian language
- [copa-sl-cer](copa-sl-cer/) - The Cerkno dialect of the Slovenian language
- [copa-hr](copa-hr/) - Croatian language
- [copa-sr](copa-sr/) - Serbian language
- [copa-sr-tor](copa-sr-tor/) - The Torlak dialect of the Serbian, Macedonian, Bulgarian language
- [copa-mk](copa-mk/) - Macedonian language

In the testing phase of the shared task, test data from the copa-sl-cer and the copa-sr-tor datasets will be shared with the participants, along with the test data of the copa-hr-ckm dataset, the surprise dialect of the shared task - the Chakavian dialect of the Croatian language.

## Examples from the datasets

For participants to get a feeling on the level of diversity in the data, below we are giving a few examples. Note that here also an example of the "surprise" Chakavian Croatian dialect is given.

### Premise and correct alternative from the first instance in the validation dataset

- English: The man turned on the faucet. Water flowed from the spout.
- Slovenian: Moški je odprl pipo. Iz ustja pipe je pritekla voda.
- Cerkno dialect: Dic je adparu pipa. Iz pipe je partjekla uoda.
- Croatian: Muškarac je otvorio slavinu. Voda je potekla iz mlaznice.
- Chakavian dialect: Muški je otpra špino. Oda je počela teć z mlaznici.
- Serbian: Човек је отворио славину. Вода је текла из славине.
- Serbian (transliterated): Čovek je otvorio slavinu. Voda je tekla iz slavine.
- Torlak dialect: Човек одврнуја славину. Вода истичала од славину.
- Torlak dialect (transliterated): Čovek odvrnuja slavinu. Voda ističala od slavinu.
- Macedonian: Човекот ја отвори славината. Истече вода од славината.
- Macedonian (transliterated): Čovekot ja otvori slavinata. Isteče voda od slavinata.

### Premise and correct alternative from the second instance in the validation dataset

- English: The girl found a bug in her cereal. She lost her appetite.
- Slovenian: Dekle je v kosmičih našlo žuželko. Izgubila je apetit.
- Cerkno dialect: Zjala je najdla hruošče u kosmičih. Zgubila je apetit.
- Croatian: Djevojka je pronašla kukca u žitaricama. Izgubila je apetit.
- Chakavian dialect: Mlada je našla neko blago va žitaricah. Je zgubila tiek.
- Serbian: Девојчица је пронашла бубу у житарицама. Изгубила је апетит.
- Serbian (transliterated): Devojčica je pronašla bubu u žitaricama. Izgubila je apetit.
- Torlak dialect: Девојчица нашла бубаљку међу њојне житарице. Изгубила си апетит.
- Torlak dialect (transliterated): Devojčica našla bubaljku među njojne žitarice. Izgubila si apetit.
- Macedonian: Девојката пронајде бубачка во нејзините житарки. Изгуби апетит.
- Macedonian (transliterated): Devojkata pronajde bubačka vo nejzinite žitarki. Izgubi apetit.

