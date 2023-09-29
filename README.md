# README

* Ruby version: 3.1.4
* Rails Version: 7.0.8
* Database: Postgresql 14.3

O start this application

- Configure **database.yml** with your postgresql's username and password
- Run the following commands in prompt/terminal

```bash
bundle install

rails db:create 
rails db:migrate 
rails db:seed

rails server
```

Routes:

- index:  GET       /api/v1/posts
- show:   GET       /api/v1/posts/:id
- create: POST      /api/v1/posts
- update: PATCH/PUT /api/v1/posts/:id
- delete: DELET     /api/v1/posts/:id
