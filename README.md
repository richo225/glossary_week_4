# Week 4 Glossary

## Projects covered

* Bookmark manager
* https://github.com/makersacademy/course/blob/master/bookmark_manager/learning_objectives.md

## Database role

![three tier web architecture 1](https://cloud.githubusercontent.com/assets/18379191/17270014/05115e84-5650-11e6-88d2-8449a0a6a700.png)

## Database terms

* **Relational database** => Organises data into tables that represent relations
  * Row => A record/single item eg.car
  * Column => An attribute of the record eg.colour, model
  * Table => Relations ie. a set of items sharing the same attributes

* **PostgresSQL** => A type of relational database

* **SQL** => Database specific language that allows you to query the database eg. CRUD

* **CRUD** => **C**reate, **R**ead, **U**pdate, **D**elete

* **psql** => Postgres command line program that lets you interact with the databse using SQL

* **ORM** => **O**bject **R**elational **M**apping
          => A technique of accessing a relational database via an OOD language

* **DataMapper** => An ORM that interacts with the databse using ruby
  * Row => Represents an instance of a class eg. Car
  * Column => Represents properties within that class eg. Car.colour, Car.model
  * Methods => Represent SQL commands eg. Car.create

* ##**MVC** => Model-View-Controller

![500px-mvc-process svg](https://cloud.githubusercontent.com/assets/18379191/17270115/13985108-5653-11e6-8c79-ae8350117797.png)

  * **Controller** => Receives input from the user and manipulates the model using commands.
  * **Model** => Manages the data, logic and rules of the application. This data is retrieved via controller commands.
  * **View** => Outputs/displays this information from the model after it's changed.
  

## Example MVC in Rails app

![mvc_rails-01 1](https://cloud.githubusercontent.com/assets/18379191/17270080/b1fb4654-5651-11e6-80d6-3ba46633a5da.jpg)
