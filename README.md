# Search-Engine

													                          							    ######################################
                                                    ###       			       ###
                                                    ###   VIRAL MEHTA  2014A7PS865H    ###
						    ###   YASH BANSAL  2014A7PS119H    ###
                                                    ###                                ###
                                                    ######################################
    

Files included in the package

-  50 CORPUS Files ['1.txt' ... to ... [50.txt]]
-  porter.py
-  indexer.py

Requirements

- required python 3.0 or later
- nltk 
- linux , windows or mac OS



-----------------------------
PROCEDURE TO COMPILE AND RUN
-----------------------------

	1 ) ensure that you have nltk already downloaded on your system
		To do that run python Console or IDLE and type :
		
		import nltk
		nltk.download('punkt')
		
		This will download the require library packages
	
    2 ) Open indexer.py from the package
		Make sure that all the data-files and porter.py must be in the same folder as of indexer.py
		Run the program using F5 Key.
		
    3 ) User would be prompted to enter the queries one by one. When a query is entered , all 
		relevant documents are printed in the order of decreasing tf-idf value. This model is implemented
		on Rank Retrieval Vector Space Model.
	
------------------
EXAMPLE
------------------

Done indexing

Enter Query:
segment tree

Showing results for: 
segment tree 
The results are:
1.	--> Document ID IS :: 27
2.	--> Document ID IS :: 34
3.	--> Document ID IS :: 33
4.	--> Document ID IS :: 10
5.	--> Document ID IS :: 39
6.	--> Document ID IS :: 9
7.	--> Document ID IS :: 19
8.	--> Document ID IS :: 44
9.	--> Document ID IS :: 45
10.	--> Document ID IS :: 16
11.	--> Document ID IS :: 7
12.	--> Document ID IS :: 8
13.	--> Document ID IS :: 42
14.	--> Document ID IS :: 50
15.	--> Document ID IS :: 4
16.	--> Document ID IS :: 1
17.	--> Document ID IS :: 40
18.	--> Document ID IS :: 32
19.	--> Document ID IS :: 29
20.	--> Document ID IS :: 20
21.	--> Document ID IS :: 13
22.	--> Document ID IS :: 28

Enter Query:
dynamic programming

Showing results for: 
dynam program 
The results are:
1.	--> Document ID IS :: 14
2.	--> Document ID IS :: 1
3.	--> Document ID IS :: 37
4.	--> Document ID IS :: 27
5.	--> Document ID IS :: 3
6.	--> Document ID IS :: 34
7.	--> Document ID IS :: 13
8.	--> Document ID IS :: 46
9.	--> Document ID IS :: 9
10.	--> Document ID IS :: 12
11.	--> Document ID IS :: 4
12.	--> Document ID IS :: 26
13.	--> Document ID IS :: 42
14.	--> Document ID IS :: 44
15.	--> Document ID IS :: 5
16.	--> Document ID IS :: 47
17.	--> Document ID IS :: 48
18.	--> Document ID IS :: 22
19.	--> Document ID IS :: 32
20.	--> Document ID IS :: 15
21.	--> Document ID IS :: 16
22.	--> Document ID IS :: 45
23.	--> Document ID IS :: 31
24.	--> Document ID IS :: 36
25.	--> Document ID IS :: 2
26.	--> Document ID IS :: 10
27.	--> Document ID IS :: 23
28.	--> Document ID IS :: 24
29.	--> Document ID IS :: 20
30.	--> Document ID IS :: 19
31.	--> Document ID IS :: 7
32.	--> Document ID IS :: 33
33.	--> Document ID IS :: 21
34.	--> Document ID IS :: 35
35.	--> Document ID IS :: 8
36.	--> Document ID IS :: 11
37.	--> Document ID IS :: 38
38.	--> Document ID IS :: 40
39.	--> Document ID IS :: 30
40.	--> Document ID IS :: 18
41.	--> Document ID IS :: 28
42.	--> Document ID IS :: 50
43.	--> Document ID IS :: 43
44.	--> Document ID IS :: 17
45.	--> Document ID IS :: 6
46.	--> Document ID IS :: 49
47.	--> Document ID IS :: 39
48.	--> Document ID IS :: 25
49.	--> Document ID IS :: 29
50.	--> Document ID IS :: 41





Package Dependencies


				|-------------------------|             |------------|
                |     indexer.py          |------------>|  porter.py |
                |-------------------------|             |------------|

				
-----------------------
Word Frequency Analysis 
-----------------------

These were the steps to the process:
    1 ) run word-count on each essay
    2 ) record the frequency for each word in a dictionary data structure
    3 ) anaylze by comparing tf-idf values 




		
