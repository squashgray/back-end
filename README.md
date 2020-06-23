# Troll Hub API

---
*Published URL = https://troll-hub.herokuapp.com/*

--- 
Schemas 
User Schema: 
{ 
  fistName: string,
  lastName: string,
  email: string,
  country: string,
  password: string,

}

__Base URL = https://troll-hub.herokuapp.com/api__

1. Creation/Login Flow ~~ RestAPI ~~ See Charts for Endpoints

|      Endpoints       | Method|            Other                |
| :------------------: | :----:| :-----------------------------: |
|   /auth/register     |  POST |  Registers a User with Token    |
|   /auth/login        |  POST |  Logins a User with Token       |


2. User Routes ~~ RestAPI ~~ See Chart for Endpoints


|      Endpoints       | Method|            Other                |
| :------------------: | :----:| :-----------------------------: |
|      /newUser        | GET   |     Gets a List of Users        |
|      /newUser/:id    | GET   |      Gets a User By Id          |
|      /:id/favorites  | GET   |      Gets a Users Favorite Comment |
|      /newUser/:id    | PUT   |        Edits a User             |
|      /newUser/:id    |DELETE |        Deletes a User           |

3. Comment Routes ~~ RestAPI ~~ See Chart for Endpoints

|      Endpoints       | Method|            Other                |
| :------------------: | :----:| :-----------------------------: |
|    /comments         |  GET  | Gets all Comments for DS API    |

4. Favorites Comment Routes ~~RestAPI ~~ See Chart for Endpoints

|      Endpoints       | Method|            Other                |
| :------------------: | :----:| :-----------------------------: |
|    /favorites        |  GET  |   Gets a Comment By ID          |
|    /favorites        | POST  |   Saves A Comment to UserFavs   |
|    /favorites/:id    | DELETE |  Deletes a Comment             |
