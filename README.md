Narrative Report: Object-Oriented Programming in PHP (Activities 1 & 2)

This report details the implementation and functionality of the provided PHP code snippets for Activities 1 and 2. Both activities demonstrate fundamental object-oriented programming (OOP) principles through the creation and utilization of custom classes.

Activity 1: The  Product  Class

![image](https://github.com/user-attachments/assets/606ce73e-6d8f-4e11-aef4-cd66fa7aa1b5)
![image](https://github.com/user-attachments/assets/fcd3fc9d-ff78-4f0a-a9bf-0daa43925685)

Activity 1 introduces a  Product  class designed to manage product information.  The class encapsulates five key attributes:  name ,  description ,  price ,  category , and  stock .  These attributes are defined as public properties, allowing direct access.
 
The code utilizes two primary methods:
-  setProduct() : This method acts as a constructor, assigning values to the product's attributes.  It takes five arguments corresponding to each attribute and sets the respective class properties.
-  getProductInfo() : This method returns a formatted string containing all the product's information.  The output is organized for readability, with each attribute displayed on a new line, enhancing clarity.
An instance of the  Product  class is created, representing a "Laptop" product.  The  setProduct()  method initializes the object's attributes, and  getProductInfo()  displays the complete product details to the console.  This demonstrates the core OOP concepts of encapsulation and data abstraction.
 
Activity 2: The  Movie  Class

![image](https://github.com/user-attachments/assets/6ce9b690-2b35-4982-a42e-fb5c7c6515e9)
![image](https://github.com/user-attachments/assets/06e32367-045b-46f9-8492-5ec447712bc7)

Activity 2 mirrors the structure of Activity 1 but focuses on a  Movie  class.  This class manages movie-related data, including  title ,  director ,  genre ,  year , and  rating .  Similar to the  Product  class, these attributes are public properties.



The  Movie  class also employs two methods:
-  setMovie() :  This method, functioning similarly to  setProduct() , initializes the movie object's attributes using five arguments.
-  getMovieInfo() : This method returns a formatted string displaying the movie's information, maintaining a consistent output style with Activity 1.
An instance of the  Movie  class is created for "The Shawshank Redemption."  The  setMovie()  method sets the attributes, and  getMovieInfo()  displays the complete movie details.
 
Comparison and Analysis:
Both activities effectively demonstrate the application of OOP principles.  The similar structure of the  Product  and  Movie  classes highlights the reusability and adaptability of OOP.  The consistent use of methods to set and retrieve information promotes maintainability and code organization.  The clear formatting of the output in both activities enhances the user experience.
 
Conclusion:
The provided code snippets offer a clear and concise introduction to OOP concepts in PHP.  The use of separate classes for different data types (products and movies) showcases the power and flexibility of OOP in managing and organizing complex data structures.  The well-structured code and clear output contribute to the overall effectiveness of these examples.

Submitted by:
   Angel Erica L. Uanang
