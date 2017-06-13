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

### Setting up our Project
#### Quickstart for Google Cloud Platform on Windows - [https://cloud.google.com/sdk/docs/quickstart-windows]
1. Initialize the SDK:

Run the following at a command prompt:
`gcloud init`

2. Accept the option to log in using your Google user account:

`To continue, you must log in. Would you like to log in (Y/n)? Y`

3. In your browser, log in to your Google user account when prompted and click Allow to grant permission to access Google Cloud Platform resources.

At the command prompt, select a Cloud Platform project from the list of those where you have Owner, Editor or Viewer permissions:
```
Pick cloud project to use:
 [1] [my-project-1]
 [2] [my-project-2]
 ...
 Please enter your numeric choice:
```

4. If you only have one project, gcloud init selects it for you.

If you have the Google Compute Engine API enabled, gcloud init allows you to choose a default Compute Engine zone:
```
Which compute zone would you like to use as project default?
 [1] [asia-east1-a]
 [2] [asia-east1-b]
 ...
 [14] Do not use default zone
 Please enter your numeric choice:
```

5. `gcloud init` confirms that you have complete the setup steps successfully:

```
gcloud has now been configured!
You can use [gcloud config] to change more gcloud settings.

Your active configuration is: [default]
```

### Run core gcloud commands

1. Run these gcloud commands to view information about your SDK installation:

* To list accounts whose credentials are stored on the local system:

`gcloud auth list`
gcloud displays a list of credentialed accounts:

```
Credentialed accounts:
 - example-user-1@gmail.com (active)
 - example-user-2@gmail.com

```

2. To list the properties in your active SDK configuration:

`gcloud config list`

gcloud displays the list of properties:

```
[core]
account = example-user-1@gmail.com
disable_usage_reporting = False
project = example-project
```

3. To view information your Cloud SDK installation and the active SDK configuration:

`gcloud info`
gcloud displays a summary of information about your Cloud SDK installation. This includes information about your system, the installed SDK components, the active user account and current project, and the properties in the active SDK configuration.

To view information about gcloud commands and other topics from the command line:
`gcloud help`

For example, to view the help for gcloud compute instances create:
`gcloud help compute instances create`

`gcloud` displays a help topic that contains a description of the command, a list of command flags and arguments, and examples of how to use it.


### Conclusion
Let Google run and scale the infrastructure while we focus on your application's features, not on managing infrastructure that runs our app.
