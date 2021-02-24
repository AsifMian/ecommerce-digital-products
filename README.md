# ecommerce-digital-products
I developed this application at xlogic solutions Using laravel Framework\
  Basically there were two types of products having different logic to implement\
  ```
    1.code type
    2.Code+Api type
 ```
 ## Part of Requirements:
 ```
 1) Adding the new product will have its own path to the CFG file
 2) UNIX absolute path in the server
 3) We need the ability to select or add the duration for each product while adding from the backend and admin will be selecting the duration. every product will have its own duration.
4) We need the ability to enable certain products to be available for guest users or only for registered users or for all of the users.
5) We need to generate the code line whenever a new product is purchased and the line would be having the duration of that product.
6) Should be in PHP 7.* version and ubuntu along with Mysql.
 ```
 ## Short Description:
 ```
 When ever user purchase a one of two type digital products a unique serial code generated according to the client requirements and that was saved 
 to a .cfg file ## cfg file path will be given Admin at the time of admin adding the product the path can be reltive or absolute and that path can be same for all products 
 can vary according to products.
 
 1. When Code Type product will be purchased a verification email is sent to user with serial code and user can access the code in his user panel
 2. When Code+API Type product same procedure but for this type and API call is made on purchase if Admin has enabled the Force Activation of the product otherwise user will see Activation button on his/her panel to active the product if already activated user will be able to reactivate the product And we have to save the api response to show the user accordingly....
 3. Some other cool requirements were there...but overall it was fun to develop this project
 ```
[written [tutorial](https://github.com/AsifMian/ecommerce-digital-products/blob/main/How%20to%20deploy%20the%20digital.docx) for client to upload on vps (he wanted to upload it for his resellers by himself)]
## User Panel
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/9.png)<br>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/1.png)
## Purchase history
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/2.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/3.png)

## Digital product purchased detaial and their Activation keys (generated At the time of purchase according to client requirement)<br>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/4.png)<br>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/5.png)<br>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/7.png)<br>

## Profile Management and support ticket<br>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/8.png)<br>

# Some pic's from Admin panel<br/>

![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/10.png)<br/>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/11.png)<br/>
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/12.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/13.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/14.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/16.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/15.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/17.png)
![alt text](https://github.com/AsifMian/ecommerce-digital-products/blob/main/18.png)


```
Code in My private repository
https://github.com/AsifMian/digital-products-ecommerce-xlogic

```
