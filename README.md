# Strategy Hospital
#### This frontend repo is created to be used in conjunction with [kenngibbs/django_hospital_server](https://github.com/kenngibbs/django_hospital_server/ "kenngibbs/django_hospital_server"). They are separted so it can be hosted on Netlify

### Frontend: React, React Router

This application allows a user to create a new hospital contact and select which hospitals they are associated with. After validating the user, the dashboard shows statistics related to each hospital associated with the user: average staff salary, highest paid staff member, average procedure cost, highest cost procedure, and the total number of procedures.

The frontend currently does not allow for a user/contact to add Staff, Procedures, and Procedure Categories.

### Phase 1 (current phase):
- Create a detailed hospital page where a user can CRUD staff and procedures for the selected hospital.
- Valid a new procedure against the procedure categories.

### Phase 2:
- Allow a new contact to select a hospital group that will automatically select all of the hospitals under it.
- Create a different portal for administration users to CRUD hospitals and hospital groups.

### Additional Thoughts
- Maybe procedure categories should be per hospital or hospital group. I doubt the max/min of a procedure will be default across the board. Maybe there should be both global and "local" procedure cost validation.

## To run the application:
Once the application is cloned or downloaded use the terminal/console to navigate to the react_hospital_client directory and run ```npm install``` or ```yarn install```. Once it's complete run ```npm start``` or ```yarn start```.
