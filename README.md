# Challenge-Jr-Backend

<p>
  1. You're building a high-throughput API for a cryptocurrency trading platform. For this platform, time is extremely important because microseconds count when processing high-volume trade orders. For communicating with the API, you want to choose the verb that is fastest for read-only operations. What verb should you choose for retrieveing trade orders with the API server?<br>
Answer: Option 1, since GET is the only HTTP function that retrieves information.</p>
<br>
<p>
  2. You work for a Customer Relationship Management (CRM) company. The company's clients gain CRM access through a RESTful API. The CRM allows clients to add contact information for customers, prospects, and related persons (e.g., virtual assistants or marketing directors). You want to choose an appropiate API request path so clients can easily retireve information for a single contact while also being flexible for future software changes. Which of the following API paths should you use?<br>
Answer: Option 1, the company wants a way to add contact information to a specific customer, not the other way around. It's also important to keep in mind that we need that specific customer id, or else the data will be added to every user.</p>
<br>
<p>
  3. You work for a large social media network, and you've been tasked with error handling for the API. You're trying to decide on an appropriate errorcode for authentication failures based on non-existent users and incorrect passwords. You want to balance security against brute force attacks with providins descriptive and true error codes. Which HTTP error code(s) should you use to keep the system secure and still report that an error occurred?<br>
Answer: Option 2.</p>
<br>
<p>
  4. You're writing documentation for requestiing information about a given user in your system. Your system uses UUIDS (universally unique identifiers) as user identifiers. In your documentation, you want to show an example. True or false: You should put a fake UUID into the example code (instead of just the text "UUID") as a placeholder.<br>
Answer: Option 1.</p>
<br>
<p>
  5. You're building code to handle errors issued from a remote API server. The response may or may not have an error. How much work should your method, handleErrors(response), handle?<br>
Answer: Option 2, since the function its mainly to catch the error and by following best practices, its better to throw an exception to handle it in our main program.</p>
<br>
<p>
  6. You have two classes: a database driver and an email driver. Both classes need to set errors so that your front-end interface displays any errors that transpire on your platform. Which way should you implement this error handling?<br>
Answer: Option 3, as both classes are driver-based, it's convinient to code an error handler for driver-based classes, as it would help to maintain encapsulation.</p>
<br>
<p>
  7. You need to name the private method in your class that handles looping through eCommerce products to collect and parse data. That data gets stored in an array and set as a class propery. Which of the following should you use to name your method?<br>
Answer: Option 3, function naming should be done plain and simple, while maintaining the ability to inform its purpose. Thus, "parsing data" allows the developer to understand that the function will loop through a collection and parse it.</p>
<br>
<p>8. There are multiple places in your codebase that need to access the database. To access the database, you need to supply credentials. You want to balance security with useability. What strategy should you use to store and access these credentials?<br>
Answer: Option 4, for security reasons, it's better to create a .env file, as keys for database access tends to be environmental data, for later to be handled by a database service provider allowing this configuration file to be far from attackers.</p>
