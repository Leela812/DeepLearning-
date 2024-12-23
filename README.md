# TranslationMachineMultiLingual
for English to German and French we used t5-small model and this needs to be run with tensorflows==4.17
for Persian and Hindi you can use the latest update of transformers 
# Huggingface AIPI
you need to install these libraries :
transformers
gradio
torch
sentencepiece(required for Hindi and Persian)

 Model :
 
 1- Transformer Align Model 
 
 2- t5-small

  3- Proposed Multi_head self_attention Bidirectional LSTm in encoder and LSTM in decoder 
 
# compare the performance of Sequence to Squence LSTM and our Proposal Model in compare folder



 datasets:

 
 "opus_books", "en-fr"

 
 bbaaaa/iwslt14-de-en

 
 cfilt/iitb-english-hindi
