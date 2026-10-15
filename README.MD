# Deploying a text-to-SQL agent with private VPC access to RDS PostgreSQL on Amazon Bedrock AgentCore

A Strands agent deployed to Amazon Bedrock AgentCore Runtime that translates natural language questions into SQL queries against an RDS PostgreSQL database. 
The agent runs in a private VPC subnet with access to the database over the local network and to AWS services through a NAT Gateway.

Full details in the [blog post](https://flaviagiammarino.com/blog/postgresql_agent.html).

<img src=https://machine-learning-blog.s3.eu-west-2.amazonaws.com/postgresql_agent/architecture_diagram.png style="width:100%;margin-top:60px;margin-bottom:50px"/>

