# README

This is a calendar application that:

- Takes as input an array of objects.
- Each object contains a start time and an end time for the event.
- When two events collide they appear next to each other, otherwise the calendar event blocks sit on top of each other.
- Try to replicate as much as possible the layout in the attached image.


To install the required Gems:

1. Type 'bundle' in your console
2. Type 'rake db:create' to create the database
3. Type 'rake db:migrate' to migrate tables
4. Type 'rake db:seed' to seed in pre-loaded data
5. Type 'rails s' to start the server
