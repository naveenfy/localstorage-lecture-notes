Local Storage
1. How to store data in localStorage
2. how to retrieve the data
3. JSON
4. some examples


#LocalStorage:
0. we should not sensitive information/private data
1. Store the data in frontend
2. we store in key-value pairs
3. there is no expiration date
4. sotrage limit depends on browser
5. we can store only strings and numbers 
    for others JSON.stringify() to store 
     to retrive JSON.parse();

Limitations: 
1. Limited size,
2. we insecure data


JSON: 
1. Javascript object notation
2. A lang for frontend to backend to communicate (English for humans)
eg: 
    {
        "name": 'naveen",
        "roll": 123,
        "hobbies":  ['cricket', 'basketball'],
        'location': {
            "lat": "",
            "long": ""
        }
    }
3. Diff b/w JS objects and JSON
    - Any lang can understand Python, java, C++, C
    - JSON keys has quotations
    - JS objects has JS specific funtions
    