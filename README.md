API TESTING

Project Description: 
    I have performed demo api testing with postman with both environment file and csv file and generated results
    using newman with 100% success and 0 errors

Walk-through

      1.Used api from https://restful-booker.herokuapp.com/ and information about api is in API Testing.pdf file
      
      2.project has 7 HTTP requests
      1st.postman_collection.json :        api testing with generating data and storing in environment
      1stcsv.postman_collection.json:      api testing using csv file
      
![1](https://github.com/nahidanik97/api-testing/assets/157117314/5cb1fd98-9ecf-48cb-a5c4-687a6cfac635)
       
      3.HTTP request: create(POST)
      for 1st.postman_collection.json created body data from pre request script and saved in environment file
![4](https://github.com/nahidanik97/api-testing/assets/157117314/81b36862-b2a9-407d-bf41-46e3097dbcff)
![3](https://github.com/nahidanik97/api-testing/assets/157117314/4c4e7d76-f246-4c70-8369-241248eccb3e)
![2](https://github.com/nahidanik97/api-testing/assets/157117314/7737b1c7-87a2-45af-bae3-73969fa3248b)
         
         for 1stcsv.postman_collection.json data is taken from csv file
![5](https://github.com/nahidanik97/api-testing/assets/157117314/e379fcc2-65ef-4be3-a32c-da9165c4a65a)

          
      4.HTTP request: get(GET)
      tested all attributes and status code
![6](https://github.com/nahidanik97/api-testing/assets/157117314/b5c941f1-39ed-425b-8010-5d9d4f2190cb)
         
      5.HTTP request: auth(POST)
      generated token for update and delete HTTP requests
![7](https://github.com/nahidanik97/api-testing/assets/157117314/3904161a-780d-416c-a8a2-580f2e58b5e4)
      
      6.HTTP request: update(PUT)
      used the generated token to update values in the similar manner with using token in header
      7.HTTP request: verify update(GET)
      tested all attributes and status code after update
![8](https://github.com/nahidanik97/api-testing/assets/157117314/316217d3-a45a-4604-9fe8-3e165d89fed2)
    
      8.HTTP request: delete(DEL)
      deleted all data
![9](https://github.com/nahidanik97/api-testing/assets/157117314/e8b043f6-75fb-4b4e-bf15-6f11dabe017b)
      
      9.HTTP request: verify after delete(GET)
      tested if deletion is succesful or not
 ![10](https://github.com/nahidanik97/api-testing/assets/157117314/bbb1b6f6-e4a9-4a45-8139-e699556e202e)     
            
      10.Result after running entire collection of 1stcsv.postman_collection.json with csv file
 ![1](https://github.com/nahidanik97/api-testing/assets/157117314/8ebfcfc4-3974-41bc-8cf0-4563fad9b122)

      
      11.report generation of 1st.postman_collection.json using newman
![11](https://github.com/nahidanik97/api-testing/assets/157117314/953636a8-517a-47ba-9f9e-baa12e52fc61)
      


