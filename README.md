# Allergies - Backend 

This project serves as the backend for the Allergies front-end. It contains a database of 2500 recipes and contains an JSON file that can be used to seed even more. 

## Getting Started

Easiest way to ensure that you have adequate environment is to use RVM.

### Prerequisites

Using Rails v. 5.1.4 and  Ruby v. 2.3. 


### Installing

First run: bundle install

```
$ bundle install
```

Create the database and run the migrations: 

```
$ rails db:create
$ rails db:migrate
```

Before you seed the database, check out ./db/seeds.rb
Currently the rake task will run up to the first 2,500 recipes. However, the full JSON file contains over 10,000 recipes. 
Note* do not try to open the JSON file using Atom or Sublime, the size of the JSON will crash the text editor.
When you are ready, run:

```
$ rails db:seed
```
You can run `rake` in place of `rails`, it makes no difference.  


## Deployment

If there is nothing else running on port 3000, simply run:
```
$ rails s
```

## Built With

* Ruby on Rails
* PostgreSQL

## Versioning

Latest version is always available under the master branch in this repository. 

## Authors

Kenny Lin
Kesean Woodhouse - https://github.com/kesean


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Flatiron School and especially Kesean Woodhouse for seeing this project through. 
