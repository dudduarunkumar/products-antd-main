1. Project Title: Product Management Application

2. Description: Product Management Application displays the product which were created by user. 
.   In main page all products are displayed .
.   It consits "add product" button to create the product and search input field to search the products based on product name.
.    Also consist of dropdown to filter the products based on category. 
.    And Reset button to reset the application.

    when we click on "Add Product" button it opens the modal it consits of required fields to create the product.
    Name input field to enter the name of the product and description input field to enter the description about the product and one dropdown box used for select the which category of the product and price input field to enter the cost of the prodcut.

    For all those input fields validation also given with proper naming. After creating the product it displayed in the main page.
    Also it contains edit and delete buttons to edit the perticular product and delete the perticular product. 

    Localstorage used for store the data.

    Search functionaly added to search the perticular product based on the product name.

    filter function added to filter the product based on category of product.

    React Context Api is used for state management to use state whereever we want.

3. Overview of File / Folder Structure and libraries used: I created one folder name "src" . In the src folder , created different files which are useful to application.
For state managemet React context Api used to store the data of application. 
ProductListPage file is used for dispaly the products and AddProductPage file is used for create the product with multiple input and dropdowns. 

libraries :
React-router-dom: which is used for navigate to one page to another page
antd: for flexible theme customisation
react-highlight-words: React component to highlight words within larger body of text