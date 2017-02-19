Source code and data set of my thesis submitted to Nanjing University of Posts and Telecommunications for the degree of master of engineering

1.The file folder "RSLocatorSystem" is the prototype system in my thesis. It's a MyEclipse project. You can import it into your MyEclipse and run it.

2.The file folder "trial" contains data set and source code of trials in my thesis. 

(1)Query set and Corpus of Apache Spark are in the "SparkDataSet". Bug reports of 1.6.0 and 1.6.1 are in the file "bugReport.txt". Source code of 1.5.2 is in the file "sourceCode.txt", and the file paths are in the file "path.txt" in the same order. The file "codeQuery.txt", "codeCorpus.txt", "componentQuery.txt", "componentCorpus.txt", "identifierQuery.txt", "identifierCorpus.txt" are preprocessed queries and corpus, which is able to be used to conduct experiments.

(2)The preprocess scipts are in the "preprocess" file folder, which is writeen by Python. To run these scripts, you need to implement NLTK. The "reportPreprocess.py" is used to preprocess bug reports, and "srcPreprocess.py" is used to preprocess source code file. In this trial, all the reports are in the one file. One report is in a line. So did the source code.

(3)"BM25" and "VSM" are the information retrieve models. You need to create two files named "query.txt" and "corpus.txt".

(4)The Ranking SVM tool is in the file folder "ranking SVM". Its author is  Thorsten Joachims(http://www.cs.cornell.edu/people/tj/svm_light/svm_rank.html). In my trial, I used the linux version. And you need to run a shell script.

(5)To evalute the performance of trial, you need a small programme, and it's in the "Evalution". It's writeen in Java.To run it, you need to change some variables in the "PublicValue.java".
