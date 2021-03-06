# Has-Many-Through

This is boilerplate code for a has-many-through relationship. Make sure you `fork` the file to your repo!

You can define your models in the three files in folder `app/models` and then, test your code in the `tools/console.rb` file.

To run your code, type `ruby tools/console.rb` from the root directory in your terminal.

Here are some potential models you might use (The order of the models are random):

- Doctor, Patient, Appointment
- Artist, Genre, Song
- Recipe, Ingredient, Quantity
- Classroom, Student, Teacher
- Subscription, Magazine, Person
- Club, Student, Membership

When creating the models, be sure to include rich instance variables, so you can do more with the models! For instance, a `doctor` model might have things like name, field (field of study), and cost while a `patient` model might have things like name, ailments and income. In doing this, you might want to write methods where a patient can find the doctors (s)he can afford and/or a doctor appropriate for his/her pain.

There are no restrictions and no tests, so it's up to you to decide how to implement this!

~~~~~~~~~~~~

Student Note: FIles have been updated to represent the relationship that riders have with scooters they can rent through an app. 

A single rider rides many scooters over the course of a year. A single scooter has multiple riders over the course of a year. 
These two objects come together via rides, our reference object. 
