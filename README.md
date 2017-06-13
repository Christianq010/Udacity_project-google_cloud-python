# Developing Scalable Apps in Python on the Google Cloud Platform
==============================================

## Description

Build an application that can serve hundreds of thousands of users via the Google App Engine - Platform.

### *Hosted Deployed link here* -


### About Our Project

#### *1. Cloud Endpoints*
* Create API services and make them accessible to iOS, Android and Javascript clients.
* Automatically generate client libraries to make wiring up the frontend easy.

#### *2. Security*
* Denial-of-service protection.
* OAuth 2.0 support.

### _Setting up our Project_
#### Quickstart for the Google Cloud Platform on Windows

##### 1. *Initialize the SDK:* [https://cloud.google.com/sdk/docs/quickstart-windows]

* `gcloud init` - Run the following at a command prompt, log into your Google account, grant proper permissions, choose a project and complete setup successfully.

##### 2. *Launch App on Localhost:* [https://cloud.google.com/appengine/docs/standard/python/tools/using-local-server]

* `dev_appserver.py app.yaml` - Run the command as follows from the directory that contains your app's app.yaml configuration file.
* To change the port, you include the --port option:
`dev_appserver.py --port=9999 [PATH_TO_YOUR_APP]`


### __Run core gcloud commands__

##### 1. Run these gcloud commands to view information about your SDK installation:
* To list accounts whose credentials are stored on the local system:
* `gcloud auth list`- gcloud displays a list of credentialed accounts:
```
Credentialed accounts:
 - example-user-1@gmail.com (active)
 - example-user-2@gmail.com

```

##### 2. To list the properties in your active SDK configuration:
* `gcloud config list` - gcloud displays the list of properties:
```
[core]
account = example-user-1@gmail.com
disable_usage_reporting = False
project = example-project
```

##### 3. To view information your Cloud SDK installation and the active SDK configuration:
* `gcloud info` - gcloud displays a summary of information about your Cloud SDK installation. This includes information about your system, the installed SDK components, the active user account and current project, and the properties in the active SDK configuration.
* `gcloud help` - To view information about gcloud commands and other topics from the command line.
* `gcloud help compute instances create` - For example, to view the help for gcloud compute instances create.
* `gcloud` displays a help topic that contains a description of the command, a list of command flags and arguments, and examples of how to use it.


### Conclusion
Let Google run and scale the infrastructure while we focus on your application's features, not on managing infrastructure that runs our app.
