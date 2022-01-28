# hour-app-sample

This project is a tiny app where i have

* Frontend (Just a label and a button, when the button is pressed the front is going to request the time to the api)
* Backend (When necessary is going to retrieve the Hour/Time)

---

The idea is to use github actions with the following workflow

* Build
* Simulate tests
* Create artifact (Docker image)
* Publish Artifact to a private repository in Dockerhub
  * Since is a private repository in Dockerhub, secrets should be created.

Improvements:  
[ ] Create tests