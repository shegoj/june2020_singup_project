# Devops project 
## deployment steps

yum update -y
yum install python-pip
pip install flask

Git clone https://github.com/shegoj/june2020_singup_project.git code 
cd code
pip install -r requirements.txt 
export AWS_ACCESS_KEY_ID=A
export AWS_SECRET_ACCESS_KEY=w
FLASK_APP=application.py AWS_REGION=eu-xxxx-1 STARTUP_SIGNUP_TABLE=dynamo_db NEW_SIGNUP_TOPIC=arn:aws:sns:eu-west-1:xxxxxxxx:sxxxxxxxxx flask run --host 0.0.0.0

