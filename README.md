# aws-cribs-and-notes

## Serverless Application Model (SAM)

See:
- https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-getting-started-hello-world.html

Basic application setup, build, deploy
```
#Step 1 - Download a sample application
sam init

pip install -r /path/to/requirements.txt -t /path/to/build

#Step 2 - Build your application
cd sam-app
sam build [--use-container]

#Step 3 - Deploy your application
sam deploy --guided
```
