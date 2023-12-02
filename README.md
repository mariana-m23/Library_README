# Library_README
### A program that was created for the libraries of SmallTownX, it includes a new electronic rental system. The program displays the many books that are offered to be borrowed by three libraries in the town.
 #### This porgram was created by Isabella Villareal and Mariana Lozano.

#### Description: 
The program we created uses the Library and Book classes that were proivded at the beginning. It includes all the books from the Catalog File to allow the user a variety of book genres and choices. 

#### Usage: 
   The user is able to utilize this program to find the information of all the three libraries in SmallTownX, the libraries hours, location, and all the books that are available are able to be viewed by the user. This Library Program allows the user to view the Titles that are Available and even add certain Titles. Given that it indicates whether a book is available, where it is, and whether it is being borrowed, this program makes book selection easier.

#### Development: 
 We were able to develop this program by using all that was provided from the start. We began with the use of the two skeleton classes, and then began to figure out how to find the missing pieces that would allow the main method to function. We built a class that would represent the three libraries and manage the collection of books to make it easier for the user to navigate the site. Additionally, by using this action, the user can search for a book and receive a response indicating the whereabouts of the book, whether it is borrowed at the moment or it is in the second library. The library class we developed was exemplified by importing a collection of books from a catalog file through a BufferReader. For us to find the best way to import the collection from the catalog file we searched for various methods that may lead us to be able to export the books. We eventually found the most easily understood and effective technique that we thought would fit, it being the Buffer Reader. The BufferReader was the best outcome, as it is essentially a class that simplifies reading a text from character-input stream, and it uses a FileReader in order to take in all of the data. Then the BufferReader uses the FileReader to retract all the information and characters in order to adequately read the text data. Throughout our process, we added the missing pieces as we went along, implementing multiple classes, methods, and objects. 

 #### Team Work Development:
   The workload was divided between the two of us. Both Isabella and I created FileReaders, and created the objects that were missing. We ended up choosing to implement Isabella's method for the FileReader with the BufferReader. Mariana created the AvailableBooks and returnBooks. Isabella created the BorrowBook and getListOfTitles. Furthermore, by working together, we were able to test out our various approaches before deciding which would be most efficient and facilitate the smoothest operation of this program.
