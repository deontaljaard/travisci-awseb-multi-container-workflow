# Travis CI AWS Elastic Beanstalk Multi-Container Workflow

[![Build Status](https://travis-ci.com/deontaljaard/travisci-awseb-multi-container-workflow.svg?branch=main)](https://travis-ci.com/deontaljaard/travisci-awseb-multi-container-workflow)

The project houses an (over engineerd) Fibonacci calculator. Used it to learn more about a more complex CI flow.

```text
client -> nginx -> react app
                -> server    -> redis <- worker
                             -> postgres
```