Test for Java Back-end Developer - Todolist

Hi ! 
We designed this test to better understand how you approach problems solving, and how you like to code. We try to get as close as possible to our reality, using technologies that we use and that tutorials can easily be found on the internet.
If you are unable or don't want to do one of the requirements, no problem. We will not disqualify you for that. In that case you can comment on it and tell why you skipped. 
We hope you enjoy it!

Below are the tasks. 
Some of the tasks are considered as bonuses, if you do not have time or prefer not to do, you can comment on how you would do or how the technical architecture would be:

- Create an API for a whole list application. You must allow these functions: login, logout, and the functions of a simple todolist (add / edit / delete / list task with name, description, date). Use Spring BOOT;
- It can be a simple and hard coded login;
- DB is free to chose at will (suggestion h2, postgres or mongo);
- Add swagger, we should be able to do all the flow through the swagger (login, task CRUD, logout). Tip: document all fields.
- Do not forget the unit tests.
- Deliver the repository link in private mode (gitlab preference) with readme.MD with instructions on how to run locally and technical summary.

- Bonus: possibility to add attached file. If you deploy to AWS, you can save to S3, for example.
- Bonus: create dockerfile and docker-compose.yaml to deploy locally as a docker container.
- Bonus: allow user to register;
- Bonus: deploy in some cloud provider (preferably AWS, can be in EC2, or Azure or Heroku);
- Bonus: create gitlab CI / CD file with 3 stages: compile, tests (if you have unit + integration, 1 stage for each) and dockerize (generate docker container).
