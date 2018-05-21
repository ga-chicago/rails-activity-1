
# &#x2600; BLOG APP

&#x1F535; **Activity (15 mins)**

In the top level of your folder for today (NOT inside your `intro_app_api` folder)

Perform the following commands, and look back over the lesson to double-check that you are writing the correct syntax. If you get it wrong, you'll probably have to delete the app and start over. 

* Make a new Rails app called `blog_app_api`
* Remember the `--api` flag. If you forget, **delete this app and start over**
* Remember the `-d postgresql`. If you forget, **delete this app and start over**
* Create the db
* Generate a migration for creating a table called **posts**. `rails g migration CreatePosts`
* In the migration file, a post table should have columns for title, author, and content (all strings)
* Run the migration.
* Check the schema, and check the database:

`schema.rb` correct result:

![](https://i.imgur.com/IIJDqKn.png)

In `rails dbconsole`

`SELECT * FROM posts;`

Correct result:

![](https://i.imgur.com/jl6Di19.png)

<br>
<hr>
