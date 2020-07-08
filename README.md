# Devops project 
## deployment steps

1. yum update -y
2. yum install python-pip
3. pip install flask

4. git clone https://github.com/shegoj/june2020_singup_project.git code 
5. cd code
6. pip install -r requirements.txt 
7. export AWS_ACCESS_KEY_ID=A
8. export AWS_SECRET_ACCESS_KEY=w
9. FLASK_APP=application.py AWS_REGION=eu-xxxx-1 STARTUP_SIGNUP_TABLE=dynamo_db NEW_SIGNUP_TOPIC=arn:aws:sns:eu-west-1:xxxxxxxx:sxxxxxxxxx flask run --host 0.0.0.0

