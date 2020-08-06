FROM quay.io/helmpack/chart-testing:v3.0.0

ARG AWS_IAM_AUTHENTICATOR_URL=https://amazon-eks.s3.us-west-2.amazonaws.com/1.16.8/2020-04-16/bin/linux/amd64/aws-iam-authenticator

ADD ${AWS_IAM_AUTHENTICATOR_URL} /usr/local/bin/aws-iam-authenticator
RUN chmod +x /usr/local/bin/aws-iam-authenticator

WORKDIR /workdir
