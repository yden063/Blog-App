# Blog Post Application
Simple, but multi technologies stack application that allows to write blog posts, and display them in a beautiful web page. 

## How it works ?
We have three components here : 
1. The API : Back-end
2. The database
3. The front-end

___

### The API
The API is public, so no authentication.
The routes and the API are made with Express.

``` 
List posts: [GET] => /api/posts 
```

```
Add a posts: [POST] => /api/posts
```

```
Delete a post: [GET] => /api/posts/<postId>
```
___

### Database
The database used is a NoSQL database with MongoDB.

### Front-end
For the last part, I will use Vuejs.
___
## Tasks
* [~] Back-end
  * [~] API
    * [x] Connect to MongoDB
    * [x] List posts
    * [] List a specific post
    * [x] Add a post
    * [x] Delete a post
* [x] Database
  * [x] Configure MongoDB
* [ ] Front-end
  * [ ] Install Vue