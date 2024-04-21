# Practice Quiz: Graded assessment for module 3
**Total points:** 10
**Score:** 100%

## Question 1
When a Puppet agent evaluates the state of each component in the manifest, it uses gathered facts about the system to decide which rules to apply. What tool can these facts be "plugged into" in order to simplify management of the content of our Puppet configuration files?  

- Node definitions  
- Certificates  
- **Templates**  
- Modules  

## Question 2
What file extension do manifest files use?

- .exe
- .cfg
- **.pp**
- .man

## Question 3
Which of the following are valid strategies for recovery after encountering service failure? (Select all that apply.)

- **Performing a rollback to a previous version.**
- **Switching to a secondary instance.**
- **Restoring from backup.**
- Setting up monitoring and alerts.

## Question 4
What is the most important aspect of an alert?

- **It must be actionable.**
- It must require a human to be notified.
- It must require immediate action.
- It must precisely describe the cause of the issue.

## Question 5
What do rspec tests do?

- Checks that nodes can connect to the puppet master correctly.
- Check the specification of the current node.
- **Check the manifests for specific content.**
- Checks that the node is running the correct operating system.

## Question 6
Puppet facts are stored in hashes. If we wanted to use a conditional statement to perform a specific action based on a fact value, what symbol must precede the facts variable for the Puppet DSL to recognize it? 

- &
- **$**
- @
- #

## Question 7
A Puppet agent inspects /etc/conf.d, determines the OS to be Gentoo Linux, then activates the Portage package manager. What is the provider in this scenario?  

- Gentoo Linux  
- **Portage**
- The Puppet agent  
- /etc/conf.d 

## Question 8
What benefits can we gain by using automation to manage our configuration? (Check all that apply)

- **Reliability**
- **Consistency**
- **Simplicity**
- **Scalability**

## Question 9
Using a large variety of containerized applications can get complicated and messy. What are some important tips for solving problems when using containers? (Select all that apply)

- **Use extensive logging in all parts.**
- Reduce the number of containers.
- Reuse container configurations.
- **Use test instances.**

## Question 10
What are efficient ways to check the syntax of the manifest? (Check all that apply)

- **puppet parser validate.**
- **Run rspec tests.**
- **Run full No Operations simulations.**
- Test manually.