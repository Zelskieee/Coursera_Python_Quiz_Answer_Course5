# Practice Quiz: Updating Deployments
**Total points:** 5
**Score:** 100%

## Question 1
What is a production environment in Puppet?

- The software used for software development such as IDEs.
- **The parts of the infrastructure where a service is executed, and served to its users.**
- A cloud service for commercial production.
- A Virtual Machine reserved for beta software.

*Environments in Puppet are used to isolate software in development from software being served to end users.*

## Question 2
What is the --noop parameter used for?

- Passing a variable called noop to Puppet.
- Adding conditional rules to manifests.
- Defining what operations not to perform in a manifest.
- **Simulating manifest evaluation without taking any actions.**

*No Operations mode makes Puppet simulate what it would do without actually doing it.*

## Question 3
What do rspec tests do?

- Checks that nodes can connect to the puppet master correctly.
- Check the specification of the current node.
- **Check the manifests for specific content.**
- Checks that the node is running the correct operating system.

*We can test our manifests automatically by using rspec tests. In these tests, we can verify resources exist and have attributes set to specific values.*

## Question 4
How are canary environments used in testing?

- To store unused code.
- **As a test environment to detect problems before they reach the production environment.**
- As a repository for alternative coding methods for a particular problem.
- As a test environment for final software versions.

*If we can identify a problem before it reaches all the machines in the production  environment, we’ll be able to keep the problem isolated.*

## Question 5
What are efficient ways to check the syntax of the manifest? (Check all that apply)

- **Run full No Operations simulations**
- **Run rspec tests**
- Test manually
- **puppet parser validate**