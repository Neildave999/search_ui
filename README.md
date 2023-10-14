---
base_model: microsoft/SportsBERT
tags:
- generated_from_trainer
model-index:
- name: test-ner_trial
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# test-ner_trial

This model is a fine-tuned version of [microsoft/SportsBERT](https://huggingface.co/microsoft/SportsBERT) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 0.0282
- Batting Style Precision: 0.9048
- Batting Style Recall: 0.95
- Batting Style F1: 0.9268
- Batting Style Number: 20
- Bowler Style Precision: 0.9881
- Bowler Style Recall: 0.9765
- Bowler Style F1: 0.9822
- Bowler Style Number: 85
- Competition Name Precision: 1.0
- Competition Name Recall: 0.9983
- Competition Name F1: 0.9992
- Competition Name Number: 601
- Match Phase Precision: 0.9717
- Match Phase Recall: 0.9717
- Match Phase F1: 0.9717
- Match Phase Number: 106
- Outcome Precision: 1.0
- Outcome Recall: 1.0
- Outcome F1: 1.0
- Outcome Number: 64
- Player Precision: 0.9873
- Player Recall: 0.9873
- Player F1: 0.9873
- Player Number: 471
- Season Precision: 0.9941
- Season Recall: 0.9883
- Season F1: 0.9912
- Season Number: 171
- Stadium Precision: 0.9524
- Stadium Recall: 0.9615
- Stadium F1: 0.9569
- Stadium Number: 104
- Team Name Precision: 0.9937
- Team Name Recall: 0.9833
- Team Name F1: 0.9885
- Team Name Number: 480
- Overall Precision: 0.9900
- Overall Recall: 0.9872
- Overall F1: 0.9886
- Overall Accuracy: 0.9945

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 1e-05
- train_batch_size: 32
- eval_batch_size: 32
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 10.0

### Training results

| Training Loss | Epoch | Step | Validation Loss | Batting Style Precision | Batting Style Recall | Batting Style F1 | Batting Style Number | Bowler Style Precision | Bowler Style Recall | Bowler Style F1 | Bowler Style Number | Competition Name Precision | Competition Name Recall | Competition Name F1 | Competition Name Number | Match Phase Precision | Match Phase Recall | Match Phase F1 | Match Phase Number | Outcome Precision | Outcome Recall | Outcome F1 | Outcome Number | Player Precision | Player Recall | Player F1 | Player Number | Season Precision | Season Recall | Season F1 | Season Number | Stadium Precision | Stadium Recall | Stadium F1 | Stadium Number | Team Name Precision | Team Name Recall | Team Name F1 | Team Name Number | Overall Precision | Overall Recall | Overall F1 | Overall Accuracy |
|:-------------:|:-----:|:----:|:---------------:|:-----------------------:|:--------------------:|:----------------:|:--------------------:|:----------------------:|:-------------------:|:---------------:|:-------------------:|:--------------------------:|:-----------------------:|:-------------------:|:-----------------------:|:---------------------:|:------------------:|:--------------:|:------------------:|:-----------------:|:--------------:|:----------:|:--------------:|:----------------:|:-------------:|:---------:|:-------------:|:----------------:|:-------------:|:---------:|:-------------:|:-----------------:|:--------------:|:----------:|:--------------:|:-------------------:|:----------------:|:------------:|:----------------:|:-----------------:|:--------------:|:----------:|:----------------:|
| 0.579         | 1.0   | 100  | 0.0939          | 0.7273                  | 0.4                  | 0.5161           | 20                   | 0.8442                 | 0.7647              | 0.8025          | 85                  | 0.9885                     | 0.9983                  | 0.9934              | 601                     | 0.8515                | 0.8113             | 0.8309         | 106                | 1.0               | 0.9062         | 0.9508     | 64             | 0.9484           | 0.9363        | 0.9423    | 471           | 0.9709           | 0.9766        | 0.9738    | 171           | 0.8913            | 0.7885         | 0.8367     | 104            | 0.948               | 0.9875           | 0.9673       | 480              | 0.9510            | 0.9424         | 0.9467     | 0.9757           |
| 0.0774        | 2.0   | 200  | 0.0425          | 0.8636                  | 0.95                 | 0.9048           | 20                   | 0.9875                 | 0.9294              | 0.9576          | 85                  | 0.9967                     | 0.9983                  | 0.9975              | 601                     | 0.9515                | 0.9245             | 0.9378         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9662           | 0.9703        | 0.9682    | 471           | 0.9770           | 0.9942        | 0.9855    | 171           | 0.9029            | 0.8942         | 0.8986     | 104            | 0.9937              | 0.9896           | 0.9916       | 480              | 0.9790            | 0.9776         | 0.9783     | 0.9907           |
| 0.0367        | 3.0   | 300  | 0.0336          | 0.8636                  | 0.95                 | 0.9048           | 20                   | 0.9881                 | 0.9765              | 0.9822          | 85                  | 0.9967                     | 0.9983                  | 0.9975              | 601                     | 0.9346                | 0.9434             | 0.9390         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9767           | 0.9809        | 0.9788    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9126            | 0.9038         | 0.9082     | 104            | 0.9916              | 0.9896           | 0.9906       | 480              | 0.9819            | 0.9833         | 0.9826     | 0.9931           |
| 0.0252        | 4.0   | 400  | 0.0315          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 1.0                    | 0.9765              | 0.9881          | 85                  | 0.9967                     | 0.9983                  | 0.9975              | 601                     | 0.9615                | 0.9434             | 0.9524         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9892           | 0.9766        | 0.9829    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9223            | 0.9135         | 0.9179     | 104            | 0.9937              | 0.9875           | 0.9906       | 480              | 0.9880            | 0.9824         | 0.9852     | 0.9936           |
| 0.0197        | 5.0   | 500  | 0.0313          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 1.0                    | 0.9765              | 0.9881          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9808                | 0.9623             | 0.9714         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9809           | 0.9788        | 0.9798    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9798            | 0.9327         | 0.9557     | 104            | 0.9875              | 0.9896           | 0.9886       | 480              | 0.9895            | 0.9853         | 0.9874     | 0.9942           |
| 0.0152        | 6.0   | 600  | 0.0296          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 0.9882                 | 0.9882              | 0.9882          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9714                | 0.9623             | 0.9668         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9893           | 0.9830        | 0.9862    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9519            | 0.9519         | 0.9519     | 104            | 0.9937              | 0.9854           | 0.9895       | 480              | 0.9904            | 0.9867         | 0.9886     | 0.9944           |
| 0.013         | 7.0   | 700  | 0.0288          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 0.9881                 | 0.9765              | 0.9822          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9810                | 0.9717             | 0.9763         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9830           | 0.9830        | 0.9830    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9352            | 0.9712         | 0.9528     | 104            | 0.9958              | 0.9812           | 0.9885       | 480              | 0.9890            | 0.9867         | 0.9879     | 0.9944           |
| 0.0108        | 8.0   | 800  | 0.0282          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 0.9882                 | 0.9882              | 0.9882          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9810                | 0.9717             | 0.9763         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9894           | 0.9873        | 0.9883    | 471           | 0.9942           | 0.9942        | 0.9942    | 171           | 0.9615            | 0.9615         | 0.9615     | 104            | 0.9937              | 0.9833           | 0.9885       | 480              | 0.9914            | 0.9881         | 0.9898     | 0.9949           |
| 0.0104        | 9.0   | 900  | 0.0286          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 0.9881                 | 0.9765              | 0.9822          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9717                | 0.9717             | 0.9717         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9873           | 0.9894        | 0.9883    | 471           | 0.9941           | 0.9883        | 0.9912    | 171           | 0.9439            | 0.9712         | 0.9573     | 104            | 0.9958              | 0.9812           | 0.9885       | 480              | 0.9900            | 0.9876         | 0.9888     | 0.9947           |
| 0.0085        | 10.0  | 1000 | 0.0282          | 0.9048                  | 0.95                 | 0.9268           | 20                   | 0.9881                 | 0.9765              | 0.9822          | 85                  | 1.0                        | 0.9983                  | 0.9992              | 601                     | 0.9717                | 0.9717             | 0.9717         | 106                | 1.0               | 1.0            | 1.0        | 64             | 0.9873           | 0.9873        | 0.9873    | 471           | 0.9941           | 0.9883        | 0.9912    | 171           | 0.9524            | 0.9615         | 0.9569     | 104            | 0.9937              | 0.9833           | 0.9885       | 480              | 0.9900            | 0.9872         | 0.9886     | 0.9945           |


### Framework versions

- Transformers 4.34.0
- Pytorch 1.12.1+cu102
- Datasets 2.10.1
- Tokenizers 0.14.1
