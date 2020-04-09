# Building with Active Record


> Project taked from Microverse Curriculum from [The Odin Page project Site](https://github.com/MephistoDevelop/micro-reddit).

Task done as a part of the Microverse Curriculum.

Full description:

[Micro-reddit](https://www.theodinproject.com/courses/ruby-on-rails/lessons/building-with-active-record-ruby-on-rails)
-The objetive from this project is build the core of logic from Facebook page.


## Built With Ruby , Ruby on Rails, Heroku
Tools used to build Aplication:

- Ruby
- Ruby on Rails
- Heroku

 
## PROTOCOLS

- HTTP

## Getting Started

- Principal Functions:
  - Create Account Using Real Email confirmation
  - Create Login with your Facebook acccount
  - Send friends Requests
  - Views publications from others friends

#### Language Requirements

    Ruby 2.6.3
    Rails 5.2.0

#### GEMS

- Rest-client


### Setup

To use this project you will need to download this repository and put in on your computer.
after you will need to install webpack and npm to run correctlly this project.

#### Installation

Clone or download the repository to your local machine and after open your terminal on the repository folder and run :

    bundle install

    rails db:create

    rails db:migrate

    rails db:seed
    
    
#### Database Requirements

The project runs on PSQL. For running this application you must have a default PSQL role WITH LOGIN CREATEDB

For altering or creating a PSQL role run the following commands in postgres console

      For Creating a User:
      postgres=# CREATE ROLE role_name WITH LOGIN CREATEDB;

      For Altering Existing User
      postgres=# ALTER ROLE "role_name" WITH LOGIN CREATEDB;
      

### Deployment


Run:

    rails server

    enter to your:   http://localhost:3000/

### Rspec tests

    To run rspec at terminal:

      rspec

## Authors

👤 **Cristian Ines Hernandez A. - MephistoDevelop**

- Github: [@MephistoDevelop](https://github.com/MephistoDevelop)
- Twitter: [@MephistoDevelop](https://twitter.com/MephistoDevelop)
- Linkedin: [Cristian Hernandez](https://www.linkedin.com/in/cristian-hernandez1992/)

👤 **Sergio Diaz**

- GitHub: [@Sergio Diaz](https://github.com/serdg0)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](lic.url) licensed.


