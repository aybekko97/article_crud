JAVA EE - Rest API of CRUD with articles

1. Create : 
HTTP Method: POST, URL: /user/article 
HTTP Response Status Code: 201 CREATED and 409 CONFLICT 

2. Read : 
HTTP Method: GET, URL: /user/article?id={id} (Fetches article by id) 
HTTP Method: GET, URL: /user/all-articles (Fetches all articles) 
HTTP Response Status Code: 200 OK 

3. Update : 
HTTP Method: PUT, URL: /user/article 
HTTP Response Status Code: 200 OK 

4. Delete : 
HTTP Method: DELETE, URL: /user/article?id={id} 
HTTP Response Status Code: 204 NO CONTENT 
