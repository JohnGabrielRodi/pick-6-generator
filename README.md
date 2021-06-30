# pick-6-generator
A cryptographic pick-6 generator. 

I am interested in creating lottery number generators. This one returns 6 numbers using urandom(), which of necessity is looped 100 times in order to return numbers under 50. The byte-returns are converted into integers and then assembled into a list. The program is unnecessarily non-pythonic, however. I used one class and multiple methods, each method calling the next in a cascade while the program runs. The program works.  
