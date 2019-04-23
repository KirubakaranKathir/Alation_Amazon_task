# Alation_Amazon_task
Lanuage used : Java

Framework: Page Object model(POM)

POM is mainly used for enhancing test maintenanace and reducing code duplication.
We can debug easily,if any error occur while running the suite.Page Factory Class is an extension of POM,it used to initialize elements 
Here,we have used FindBy to find the locator

Package - testPages (Page Factory class)

bookDataCatalog class - This class used to choose books department in the dropdown and enter the 'data catalog' value in search button.CLick on search button
BookDetails class - This class used to get the infromation about Book details (i.e..) Title verified,Author name get and verified and edition
Kindle Details - This class used to verify the kindle tab details (i.e..) book condition,stock verify,get the price with offer,get the original price and save price,get the ebook features,supported devices link need to be verify and get soldby
PaperBackDetailUsedBook - This class used to verify the paperback used book details(i.e)book condition,stock verify,sold by,get the price,get the list of user have used book with price and Warning message for used book
PaperBackDetailsNewBook- This class used to verify the paperbook new book deatils(i.e) verify buy new radio button is clicked,old by,get the price,get the list of user have used book with price 
OtherSeller- This class used to verify the kindle and paperback new & Used book count details and price and also with total

Package - BaseTest

TestSuite class - This class used to get the class from another package with use of object creation and run the suite


Step to Execute in MAC OS:
1.Save the project (QAonsitetask)folder in local
2.Choose File-->Import-->General-->File System-->Select from location
3.Click on Run
4.Click on index.html from testoutput folder once the execution completed
5.Open with any browser..(preferable chrome/firefox)

