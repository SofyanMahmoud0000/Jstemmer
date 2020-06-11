# Stemmer

This Stemmer will help you to stem a string in addition to some features 
* Remove stop words
* Remove single letters such as (a b c d etc...) 
* Remove single numbers (1 2 3 4 5 etc...) 
* Remove undesired characters such as ($ # @ ^ % &)

## Getting started 

* Clone the repo 
* Import all libraries in the directory <ins>libs</ins>
* Import Stemmer.Stemmer
* Create a Stemmer object 
* Call the method <ins>stem</ins> 
* Enjoy!

Example: 
```java
import Stemmer.Stemmer;
        .
        .
        .
Stemmer S = new Stemmer();
String Stemmed = S.stem("The string to be stemmed")

``` 

## Running a test

We can use the main as a test for this Stemmer

Example:

![Stemmer](https://github.com/sofyanmahmoud0000/Jstemmer/blob/Main.png)

The output of this code will be 
> main function test enjoi 1234 abcd

# Build with
[Java](https://www.geeksforgeeks.org/java/) - Language used
[lucence-snowball]() - Library used to stem


## Development and support
If you have any questions on how to use this indexer, or have ideas for future development, 
please send me an e-mail to sofyan1020@gmail.com.

## Authors

***Sofyan Mahmoud*** - computer engineering 


## Licence 
MIT


