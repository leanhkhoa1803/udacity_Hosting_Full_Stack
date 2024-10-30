Pipeline Description
Developer commit code, and then will trigger a new pipeline in CircleCi
Then, the first job of pipeline is building project :
Prepare the environment like : nodejs runtime , environment variable,install required packages of both front and back end.
Run the Lint to make sure about the convention
Then build all repos (api and front end)
After building, will go to step hold on to wait for approval.
Last, deploy to AWS
Preparing all the required environment like environment variables, install nodejs runtime on EC2 instance, deploy app...
