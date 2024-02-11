# Blog Post

```
rails new blog
```
creates an blog folder and installs the necessary gemfiles to run the project

```
rails generate model BlogPost title:string body:text
```
creates an Database model inside app/model

```
rails db:migarte
```
creates or updates the Database schema

```
rails generate controller BlogPosts
```
creates an controller called **blog_posts_controller.rb**
we can pass additional arguments to create an view(template) and corresponding route for that action

```
bundle add devise
rails g devise:install
```
These command will install the *devise* gem which is used for authentiction and security things,passwords and all.

```
rails g devise User
```
creates an user Database model for authentication and stuffs



