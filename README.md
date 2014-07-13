== README


This is a simple Rails app for a Book Catalog to  be used for  a number of demos  

Ruby version 2.1.2

Data Model for Books :

Book title

Author 
 
Category

Media

valid entries for media: 'Graphic Novel',  'e-book' , 'audio book'

Category examples "sci-fi' , 'fantasy' , 'Noir' '"

To get started:

cd bookcatalog

cp config/database.yml.example config/database.yml

bundle install --without production

You may have to run: 

rake db:migrate RAILS_ENV=development


TODO: 

      rspec tests 
      Data validation        
      Make it pretty      
      authentication pages ( If I ever get round to it)      



