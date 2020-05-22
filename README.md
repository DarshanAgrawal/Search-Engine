# Search-Engine
This search engine returns the set of relevant documents out of a pool of documents when user post a query.

First run the "Inverted_Index_generation_code.py" to generate the inverted index for the documents.
Inverted index is of the form "word -> (doc_id, num_of_times_word_appear_in_that_doc)".

After that you can run "test_queries.py" to search the relevant documents for he query.

"wiki_07.txt" contains a pool of documents from which some of the documents were fetched if it matches the user's query.


Ensure that the you are using python 3

Download the following packages before proceeding 
```
pip install bs4
pip install pyspellchecker
pip install nltk
nltk.download('punkt')
pip install numpy
pip install requests
```
Both the __wiki_07 . txt__ and the **assignment . py** files must be kept in the same folder.

```
python3 assignment.py 
```
The code,by default, doesn't prints the content of the retreived documents. 
However, the content can be viewed by uncommenting the lines at the end of the following functions

main_question_1

main_question_2_improvement_1

main_question_2_improvement_2
