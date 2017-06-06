# :cloud: [Content](https://www.railstutorial.org/book/frontmatter)

* [Chap3](https://www.railstutorial.org/book/static_pages)
* [Chap4](https://www.railstutorial.org/book/rails_flavored_ruby)
* [Chap5](https://www.railstutorial.org/book/filling_in_the_layout)
* [Chap6](https://www.railstutorial.org/book/modeling_users)
* [Chap7](https://www.railstutorial.org/book/sign_up)
* [Chap8](https://www.railstutorial.org/book/basic_login)
* [Chap9](https://www.railstutorial.org/book/advanced_login)
* [Chap10](https://www.railstutorial.org/book/updating_and_deleting_users)
* [Chap11](https://www.railstutorial.org/book/account_activation)
* [Chap12](https://www.railstutorial.org/book/password_reset)
* [Chap13](https://www.railstutorial.org/book/user_microposts)
* [Chap14](https://www.railstutorial.org/book/following_users)
***

###  :anchor: *[Chap3](https://www.railstutorial.org/book/static_pages)*
:small_red_triangle_down: Summary:
* Create a Rails application from scratch , installing the necessary gems, pushing it up to a remote repository, and deploying it to production.
* Rails generate ...
* Undoing thing
* Route
* Static HTML/embedded Ruby(ERb)
* Automated testing
* Test driven development
***
<br>:small_red_triangle_down: Content: </br>

3.1. Sample app settup
* Create a Rails app from scratch:
        *rails new app_name*
* Gemfile:
    * Setup a gemfile:
        * We use the #source method for doing this:   <i>source "https://rubygems.org”</i>
    * Installing:
         *bundle install --without production*
* Pushing up to a remote repository:
        *git remote add origin git@bitbucket.org:<username>/sample_app.git*
        *git push -u origin namebranch*
* Deploying to heroku:
        *heroku create*
        *git push heroku master*
* Routing:
    * Help determine the flow of the application
    * Located in the file: <i>config/routes.rb</i>
    * Syntax:  <i>http_method 'url_format' => 'controller#action'</i>
3.2. Static pages
* Generate:
    * Controler:  <i>rails generate controller StaticPages home help</i>
    * Model: <i>rails generate model User name:string email:string</i>
* Destroy:
    * Controler: <i>rails destroy  controller StaticPages home help</i>
    * Model: <i>rails destroy model User</i>




