## Keywords repository
This is an initial repository generated for hosting the keywords, which will be used in the processes of data submission and data query within the Hydralab+ research database.
## The purpose of the keywords
* __Adding metadata in upload process__:
during the process of data submission, attributing the datasets with standard keywords prevent the database having multiple subjective attributes for a certain concept (for example, Drag_Force, drag force or Drag). 
* __Query process__:
standard and structured keywords allow better and easier search. having keywords organised in certain types (see [The structure of keywords table](#str) heading) will facilitate the use of filters in the search process and will help the user to refine the search.

## <a name="str"></a>The structure of keywords table
each keyword entry has 5 attributes, which are listed below with an explanation
1. __Keyword lable__: is the standard phrase to be used to represent a concept.
2. __Keyword ID__: this attribute is a pointer to the keyword, which may be helpful in programming. moreover, in some cases, a keyword may have different meanings in different contexts and the keyword ID might be helpful for disambiguation in such cases. Each keyword ID starts with a 2-letter prefix, which identifies the type of keyword (for example MD for measurement device), and continue with a combination of uppercase and lowercase letters.
## How to contribute
every part of this repository is open to edition.
