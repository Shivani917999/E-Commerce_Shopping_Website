# E-Commerce_Shopping_Website

<h3> About</h3>
<p>Welcome to our E-commerce website project! Our goal is to provide users with a seamless online shopping experience where they can browse, search for, and purchase a wide range of products from the comfort of their own homes.</p>

# <h5> Features include</h5>
      
     1.    User Registration and Authentication: Users can create accounts and log in securely.
     
     2.    Browse Clothing Inventory: Browse a diverse selection of clothing items categorized by occasion, style, and size.
     
     3.    Search:Search for specific clothing items based on keywords or filters.
     
     4.    Rent Clothing: Add clothing items to your cart, specify rental duration, and complete the rental process.
     
     5.    Order Management:Users can view and manage their rental orders, including viewing rental history and extending rental periods.
     
     6.    Admin Panel: Admin users have access to an admin panel to manage clothing inventory, user accounts, and rental orders.
     
     7.    Responsive Design:The website is responsive and works seamlessly on various devices.
           Technologies Usedduct information.
      
      
<h4> Screenshots</h4>

![image](https://github.com/Shivani917999/E-Commerce_Shopping_Website/assets/157983164/997f8a55-7bea-4f24-9663-027d0d3307d5)
      
  ![image](https://github.com/Shivani917999/E-Commerce_Shopping_Website/assets/157983164/67cdea2b-118e-4552-ae46-0c624e4a04f5)
      
 ![image](https://github.com/Shivani917999/E-Commerce_Shopping_Website/assets/157983164/77ca8d48-b66a-4574-acc8-3835b70e5718)


<h4> Prerequisites</h4>

# <h5> <p>What things you need to install</p></h5>
       You need Tomcat server 8 or above installed.
       Locally installed MySQL or a MySQL server.
       Compatible IDE, Intellij IDEA recommended for this project.   
# <h5> Installing</h5> 
       For MySQL Database

          SQL script can be found in the project folder.
          SQL script doesn't contain query to create schema, you will need to create one with name jsp-servlet-ecommerce-website.
# <h5> For Tomcat Application Server</h5>

      Use Tomcat 8.5.23 or above and compile to generate WAR file.
      
     <h3> Getting Started</h3>
<p>To get this Cloth Rental Website project up and running on your local machine, follow these steps:</p>

# <h5>1.Clone this repository:</p>
          https://github.com/Shivani917999/E-Commerce_Shopping_Website.git
      
<p>2.Set up a MySQL database and create the necessary tables. You can use the provided SQL scripts in the database directory to create the schema and initial data.</p>

# <h5> 3. Configure the database connection in the web/WEB-INF/web.xml file:</h5>

             <context-param>
             <param-name>dbURL</param-name>
             <param-value>jdbc:mysql://localhost:3306/your-database-name</param-value>
             </context-param>
             <context-param>
                  <param-name>dbUser</param-name>
                  <param-value>your-username</param-value>
             </context-param>
             <context-param>
                  <param-name>dbPassword</param-name>
                  <param-value>your-password</param-value>
             </context-param>
<p> 4. Deploy the project to a servlet container like Apache Tomcat.</p>

<p> 5. Access the application in your web browser (http://localhost:8080/shoppingwebsite)</p>
       Usage 
<h3> Contributing</h3>

  <p>If you want to contribute to this project you can email me - <a href="shivani9179994889@gmail.com"></a> or you can pull request.</p>
  
<h3> Built With</h3>
<ul style="list-style-type: square;"> 
<li>Java - Oracle Java 16 JDK</li>
<li>MySQL - MySQL Database</li>
<li>Connector/J - Connecting to MySQL Database Server</li>
<li>Maven - Dependency Management</li>
<li>Shoppers - Free Bootstrap 4 HTML5 ecommerece website template - Website and css Front-end</li>
