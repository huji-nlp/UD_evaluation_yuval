# ud_evaluation
MT evaluation using UD trees

german-english_ud holds relevant data to get an evaluation of MT quality without reference

bleu_changed_for_ud is a python script that is basicaly the nltk bleu with minor changes to use the ud_bleu functions.

ud_bleu is python script that holds the ngrams function for the bleu metric and different implementations to get ngrams using the UD

train_mat are matrices that has the pos/edge type transformation matrices from german to english based on the https://linguatools.org/tools/corpora/webcrawl-parallel-corpus-german-english-2015/

two csv files that has the results for two ud_bleu metrics. 
