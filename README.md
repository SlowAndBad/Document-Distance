# Document-Distance
This program finds out the difference between two files and gives a numerical value to the difference between the two files in radians.
Both the files are converted into two vectors by using the dictionary data structure of python.
All the sentences in the files are split into induvidual words and are made case insensitive. All types of punctuations and symbols are removed from the each line of the file.
The features of these vectors are the unique words present in the file and their respective parameters are the frequency of appearence of that word in the file.
Hence the difference between the files is the cosine of the angle between the two vectors.
Coisne of the angle between the vectors is found out by taking the inner product(dot product) of the vectors and dividing it by the product of their modulus.
