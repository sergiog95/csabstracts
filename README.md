# CS Abstracts Dataset
Dataset of scientific abstracts for the purpose of sentence classification. The abstracts are from the Computer Science, 

The dataset is composed by a total of 654 abstracts, which were collected from the arXiv platform. Then, using a crowdsourcing and collective inteligence, the data was annotated, where the sentences where categorized in the following classes:
- Background
- Objective
- Methods
- Results
- Conclusions

All the abstracts are from the Computer Science field (hence the name CS Abstracts). The following table details composition of the dataset, with respective numbers of abstracts and sentences splitted by training set, validation set and test set:

|            | Training set | Validation set | Test set |
|------------|--------------|----------------|----------|
| #abstracts | 500          | 77             | 77       |
| #sentences | 3287         | 824            | 619      |

The dataset is split in three files (train.txt, validation.txt and test.txt).

Each entry in the file is one abstracts and each column is separated by a tab. The first column is the position of the sentence of the abstracts, the second column is the label/category of the sentence of the abstracts, and the third column is the text itself of the abstract sentence.

The dataset was developed in the context of my Master's Thesis in Engineering and Management of Information Systems.
