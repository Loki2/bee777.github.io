# Request header required to set:
- **Key**: **X-Requested-With**

- **Value**: **XMLHttpRequest**
# Available API URIs#:
- **Get Encoded JSON DATA of Single Article(Blog) with specific an id**:

  `http://128.199.174.192/api/home/article/id_here`
- **Get Encoded JSON DATA of All Article(Blogs) with specific Category Name and Page Number (For pagination, default page number is 1, you can leave it to empty)**:

  `http://128.199.174.192/api/home/article/category_name_here/current_page_number_here(if needed)`

 - ## Available Categories Name:
   **1. events.**
   
   **2. resume.**
   
   **3. interviews.**
   
   **4. jobs.**
   
   **5. career.**
   
   **6. salary.**
   
   ### Note:
   
   **Allowed Origins for Localhost Ports:**
   `8000,
   8080`
   
   **- Default is events.**
   
   **- All of categories name is lowercase.**
  
 ## - To Check All Available Object Keys only for Javascript use:
    console.log(JSON.parse(YourResponse.data));

 
 
 
