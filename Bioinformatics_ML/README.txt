BiGRU.ipynb walks through the construction of a Bidirectional GRU for the prediction of transcription factor (TF) binding sites. 
This implementation is based upon the work and model description given in: 

Shen Z, Bao W & Huang D-S.Recurrent Neural Network for Predicting Transcription Factor Binding Sites. Scientific Reports.  2018, 8:15270
https://www.nature.com/articles/s41598-018-33321-1

BiGRU.ipnyb requires the following ChIP-Seq dataset to run on: ELK1_GM12878_ELK1_(1277-1)_Stanford_AC (2).seq.gz
However, BiGRU.ipnyb can be easily modified to predict the TF binding sites of different ChIP-Seq datasets.
