API
===


RESTful API documentation


.. http:get:: /users/(int:user_id)/Books

   User ( 'User_id' API to get a list of books).

   **Request example**:

   .. sourcecode:: http
      
      GET /users/123/web HTTP /1.1
      Host: facebook.com
      Accept: Application / json

   **Response example**:

   .. sourcecode:: http

      HTTP/1.1 200 OK
      Vary: Accept
      Content - Type: Application / json

      [
        {
          "Book_id": 123,
          "author_id": 35,
          "Title": "Sphinx Book"
         }
      ]
   :query sort: one of ``hit``, ``created-at``
   :query offset: offset number. default is 0
   :query limit: limit number. default is 30
   :reqheader Accept: the response content type depends on
                      :mailheader:`Accept` header
   :reqheader Authorization: optional OAuth token to authenticate
   :resheader Content-Type: this depends on :mailheader:`Accept`
                            header of request
   :statuscode 200: no error
   :statuscode 404: there's no user 
