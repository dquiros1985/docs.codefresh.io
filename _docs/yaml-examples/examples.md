---
title: "Examples"
description: "A collection of examples for Codefresh pipelines"
group: yaml-examples
redirect_from:
  - /docs/examples-v01/
  - examples.html
toc: true
---
Codefresh enables you to define the steps of your pipeline in a [YAML file]({{site.baseurl}}/docs/codefresh-yaml/what-is-the-codefresh-yaml/). By default, the file is named ```codefresh.yml```, and is located in the root directory of the repository.

## Programming Language specific

Codefresh is agnostic as far as programming languages are concerned. All major programming languages are supported.

- [Node.JS app]({{site.baseurl}}/docs/learn-by-example/nodejs/lets-chat/)
- [Spring Java app]({{site.baseurl}}/docs/learn-by-example/java/spring-boot-2/)
- [Scala app]({{site.baseurl}}/docs/learn-by-example/scala/scala-hello-world/)
- [Python Django app]({{site.baseurl}}/docs/learn-by-example/python/django/)
- [Ruby On Rails app]({{site.baseurl}}/docs/learn-by-example/ruby/)
- [Go App]({{site.baseurl}}/docs/learn-by-example/golang/golang-hello-world/)

## Build

Codefresh has native support for [building]({{site.baseurl}}/docs/codefresh-yaml/steps/build-1/) and [pushing]({{site.baseurl}}/docs/codefresh-yaml/steps/push-1/) Docker containers.

- [Build an Image with the Dockerfile in Root Directory]({{site.baseurl}}/docs/yaml-examples/examples/build-an-image-dockerfile-in-root-directory/)
- [Build an Image by Specifying the Dockerfile Location]({{site.baseurl}}/docs/yaml-examples/examples/build-an-image-specify-dockerfile-location)
- [Build an Image from a Different Git Repository]({{site.baseurl}}/docs/yaml-examples/examples/build-an-image-from-a-different-git-repository)
- [Build an Image With Build Arguments]({{site.baseurl}}/docs/yaml-examples/examples/build-an-image-with-build-arguments)
- [Build and Push an Image]({{site.baseurl}}/docs/yaml-examples/examples/build-and-push-an-image)

## Workflows

- [Run command before docker build]({{site.baseurl}}/docs/yaml-examples/examples/shared-volumes-between-builds)
- [Build images in parallel]({{site.baseurl}}/docs/yaml-examples/examples/shared-volumes-between-builds)
- [Shared volumes between builds]({{site.baseurl}}/docs/yaml-examples/examples/shared-volumes-between-builds)
- [Clone private repository using freestyle step]({{site.baseurl}}/docs/yaml-examples/examples/git-clone-private-repository-using-freestyle-step)
- [Get Short SHA ID and Use it in a CI Process]({{site.baseurl}}/docs/yaml-examples/examples/get-short-sha-id-and-use-it-in-a-ci-process)
- [Call one pipeline from another]({{site.baseurl}}/docs/yaml-examples/examples/get-short-sha-id-and-use-it-in-a-ci-process)
- [Request manual approval]({{site.baseurl}}/docs/yaml-examples/examples/get-short-sha-id-and-use-it-in-a-ci-process)

## Testing

Codefresh has support for both [unit]({{site.baseurl}}/docs/testing/unit-tests/) and [integration tests]({{site.baseurl}}/docs/testing/integration-tests/) as well as [test reporting]({{site.baseurl}}/docs/testing/test-reports/).

- [Run Unit Tests]({{site.baseurl}}/docs/yaml-examples/examples/run-unit-tests) 
- [Run Unit Tests with Composition]({{site.baseurl}}/docs/yaml-examples/examples/run-unit-tests-with-composition) 
- [Run Integration Tests]({{site.baseurl}}/docs/yaml-examples/examples/run-integration-tests) 
- [Shared volumes of service from composition step for other yml steps]({{site.baseurl}}/docs/yaml-examples/examples/shared-volumes-of-service-from-composition-step-for-other-yml-steps)
- [Launch Composition]({{site.baseurl}}/docs/yaml-examples/examples/launch-composition) 
- [Launching a composition and defining a service environment variables using a file]({{site.baseurl}}/docs/yaml-examples/examples/launching-a-composition-and-defining-a-service-environment-variables-using-a-file) 
- [Populate a database with existing data]({{site.baseurl}}/docs/yaml-examples/examples/populate-a-database-with-existing-data) 

## Kubernetes Deployments

Codefresh can deploy to any platform such as VMs, FTP/SSH/S3 sites, app servers but of course it has great support for [Kubernetes clusters]({{site.baseurl}}/docs/deploy-to-kubernetes/deployment-options-to-kubernetes/) and [Helm releases]({{site.baseurl}}/docs/new-helm/helm-releases-management/)

- [Deploy Demochat to a Kubernetes cluster]({{site.baseurl}}/docs/deploy-to-kubernetes/codefresh-kubernetes-integration-demochat-example/)
- [Simple Manifest templates]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Use kubectl as part of Freestyle step]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step) 
- [Blue/Green deployment]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Canary Deployment]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)

## Helm Deployments

- [Package chart and push to Helm repository]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Push and deploy a chart to cluster]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Running custom Helm commands]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)

## Other types of Deployments

- [Deploy to VM]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Copy files to S3]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Deploy with SFTP]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)
- [Deploy with Heroku]({{site.baseurl}}/docs/yaml-examples/examples/use-kubectl-as-part-of-freestyle-step)

## Notifications

- [Sending the notification to Slack]({{site.baseurl}}/docs/yaml-examples/examples/sending-the-notification-to-slack)
