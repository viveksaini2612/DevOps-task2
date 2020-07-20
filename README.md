# DevOps-task2
DevOps Task 2 Git Jenkins Docker

Create container image that’s has Jenkins installed using docker file
When we launch this image, it should automatically start the Jenkins service in the container.
Create a job chain of job1, job2 and two more jobs using build pipeline plugin in Jenkins
Job1 - : Pull the Github repo automatically when some developers push the repo to Github.
Job2 - : By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )
Job3 : Test your app if it  is working or not.Job4 : if app is not working , then send email to developer with error messages.
Create One extra job job5 for monitor : If container where app is running. fails due to any reson then this job should automatically start the container again.
