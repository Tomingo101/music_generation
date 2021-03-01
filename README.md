# Music generation

This repo aims to present our RNN based architecture for two hands classical piano pieces automatic generation.

## Preprocessing
The "Preprocessing" folder contains notebooks to process the piano midi files available on http://piano-midi.de/.

## Right hand generation
The "Right hand generation" folder contains notebooks to generate a right hand piano melody. It provides the 3 approaches described in the article: prediction of note only, prediction of note and time, prediction of all components (note, time, duration, velocity) with a conditional structure. 

## Left hand generation
The "Left hand generation" folder contains notebooks to train the sequence to sequence model in order to generate the left hand from the right hand sequence.

## Generated music
The "Generated music" folder contains piano melodies generated by the right hand model (RNN architecture). The files are in midi format. 
* right_note_RNN.mid corresponds to the note only prediction model 
* right_note_time_RNN.mid corresponds to the note and time prediction model
* right_final_RNN.mid corresponds to the full conditional model 

We have also provided some melodies specialized on authors like Mozart or Schubert.
