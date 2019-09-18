# aws-lambda-mean-stack

Creating an automated image to install Mean Stack and configure AWS Lambda.
This method would be using a docker image, hence the first thing that needs to be done
is to create a docker image, remotely, and call it using a shell script,
and post that use YAML to configure Webpack, using NPM, and install
all the necessary dependencies.
