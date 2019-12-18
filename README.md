The text is processed and the result is stored separately for both Language Hindi & English for all following subtasks: 

Implementation (Steps):

(i) Tokenization is performed followed by pruning. Words and its frequency are stored in a text file for both language.
(Extraction of words only, No numbers or special charaters during tokenization.)

(ii) Inverted index(postings) of the extracted words are created under subtask (i) for both languages. 
Results are stored in two separate files (Postings for a term is a list of document numbers where that term occurs) 

(iii) Vector Model is constructed which takes a set of words as a query and returns the list of relevant documents using the 
weighted term-document matrix (containing tf*idf for corresponding term and document) (ii). 
