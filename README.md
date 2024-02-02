# api-testing

# Project Description
    I have performed demo api testing with postman with both environment file and csv file and generated results
    using newman with 100% success and 0 errors

# Walk-through
      1.Used api from https://restful-booker.herokuapp.com/ and information about api is in API Testing.pdf file
      2.project has 7 HTTP requests
       ![1](https://github.com/nahidanik97/api-testing/assets/157117314/5cb1fd98-9ecf-48cb-a5c4-687a6cfac635)
      3.HTTP requests create(POST)
         for 1st.postman_collection.json created body data from pre request script and saved in environment file
         for 1stcsv.postman_collection.json data is taken from csv file
          
      4.HTTP requests get(GET)
         tested all attributes and status code
      5.HTTP requests auth(POST)
         generated token for update and delete HTTP requests
      6.HTTP requests update(PUT)
         used the generated token to update values in the similar manner 
      7.HTTP requests verify update(GET)
        tested all attributes and status code after update
      8.HTTP requests delete(DEL)
        deleted all data
      9.HTTP requests verify after delete(GET)
        tested if deletion is succesful or not
      
            

# How to Install and Run the Project

# How to Use the Project


