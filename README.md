# my-aws-app

I have build a simple backend API using flask that allows basic [get],[post] and [delete] functions of products inventory.
My API is saving changes of inventory to AWS RDS Postgres DB using SQLAlchemy.

The platform is deployed to ECS container using github action and ansible playbook
This picture explains the pipline:

![flow](/pictures/flow.png)

This is a basic sketch of the deployed platform:

![app](/pictures/my-app.png)
