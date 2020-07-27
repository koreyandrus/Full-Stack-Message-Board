# Full Stack Message Board

* [x] Create Server Folder
  * [x] Init npm
  * [x] Add express morgan cors body-parser
  * [x] Create Hello World Route
* [ ] Create Client Folder
  * [x] vue create client
  * [x] Add bootswatch CSS
  * [x] Homepage Layout
* [ ] Add DB to server
  * [x] Add monk joi
  * [x] Create message model
  * [x] Create route to add message to db
    * [x] validate message with joi
      * username - default to anonymous
      * subject
      * message
      * imageURL
      * created_at
    * [x] insert message into db
    * [x] respond with inserted message
* [ ] When page loads show all messages on page
  * [ ] Server route to GET all messages
* [ ] Create new message form on client
  * [ ] Submit form - fetch POST to server
  * [ ] Show any errors
  * [ ] Show new message on page
* [ ] User can reply to a message
  * [ ] Reply appears under original message
* [ ] Group messages into categories
* [ ] Deploy!