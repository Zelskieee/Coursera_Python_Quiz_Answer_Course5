# Practice Quiz: Continuous integration
**Total points:** 5
**Score:** 100%

## Question 1
What is the role of a webhook in GitHub? 

- It serves as a version control system. 
- **It enables GitHub to notify CI tools about code changes.**
- It allows coding collaboration at scale.
- It generates new tokens so that you can connect your CI system to GitHub.

*A webhook is a URL provided to GitHub by the CI system, and it allows GitHub to notify CI tools about code changes.*

## Question 2
Which of the following are the core components of Cloud Build? Select all that apply.

- **Build triggers**
- **Build configurations**
- **Build steps**
- Build artifacts

*Build triggers, configurations, and steps all make up the core components of Cloud Build. Build triggers are events that begin the Cloud Build process. Build configurations are YAML files that define the steps and settings for your build. Build steps are the actions that Cloud Build executes in a specific order depending on the build configuration.*

## Question 3
What is the purpose of utilizing version control in continuous integration with your code? 

- It is a way to direct artifacts to the correct repository.
- **It is a way to manage code changes and to track the code’s history.**
- It is a way to receive feedback from different tests to determine what issues your code contains.
- It is a way to create multiple versions of a code and distribute the codes among stakeholders.

*Version control allows developers to view code history and manage the code changes as needed.*

## Question 4
Why should you run integration tests? Select all that apply. 

- **To catch errors earlier in the CI pipeline.**
- **To make sure your application components work together as expected.**
- To verify the functionality and performance of an entire software application from start to finish.
- To check how individual units of code are working as expected.

*You conduct integration tests to make sure the different parts of your application work together and catch errors earlier on in the CI pipeline, which can save you time, money, and a lot of headaches.*

## Question 5
You have developed new code for an application you are creating for a client. You are using the Cloud Build service supported by Google Cloud Platform, or GCP. Which step in the build steps process refers to moving the application to an environment when it is ready for production? 

- Running tests
- **Deploying**
- Fetching dependencies
- Building the application

*The last step in the build step process is to deploy the application to a specific environment for production.*