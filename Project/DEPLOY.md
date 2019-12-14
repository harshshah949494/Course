# Milestone: DEPLOYMENT

In the previous milestone, we implemented the services required for your use cases and implemented interaction with a bot. In this milestone, you will be demonstrating a fully deployed version of your bot for use in a Slack/Mattermost/Github/etc. environment.

### Deployment

Using a configuring management tool, you must fully provision and configure a remote environment for your bot. You should largely be able to reuse homework materials but adopted for your bot.

In your README.md, document how these configuration management tools and deployment scripts should be run and make sure to include demonstrate running them in your screencast.

### Acceptance Testing

For your DevBots, create a test team and a TA user account, which TAs will be using for testing your deployed bot. For github bots, grant the necessary permissions for performing tasks on a demo repository. 

Provide **login credentials** for TA.

Provide **acceptance test instructions** for TAs to evaluate your three use cases using the TA user account. The acceptance tests should provide concrete instructions on what to actions to perform and verify at each step.

##### Uptime Penalaties

Your bot should remain running in your deployed environment and be available for acceptance testing at any time after this deadline and final exam.

A non-running or crashing bot that requires a manual restart will incur a -10 penalty (Using automatic process restart tools such as forever should help avoid this).

If acceptance testing cannot be performed on a deployed manner and needs to be manually demoed during a scheduled TA office hours visit will incur a -40 penalty.

### Exploratory Testing and Code Inspection

You must not hard-code interaction/mock data for your bots. TAs will perform additional exploratory testing and code inspection to verify bots perform as expected and handle edge cases and error in inputs. 

**Failure to adhere to these instructions will result in a 0 for this milestone.**

### Bonus: Continuous Integration (CI) Server

Create a jenkins server and build job that runs a build job for your bot, including running your integration tests. 

CI can run in a local or hosted VM.

To receive create, you must demonstate your CI working based on a build running from a triggered commit, and show build logs with passing integration tests.

### Submit

In your repository, create a new markdown file, DEPLOY.md, with descriptions about the following:

* Deployment scripts
* Acceptance tests
* Final code
* Optional bonus: Code and screencast for continuous integration server.

Due Sunday, December 1st, before midnight.

### Evaluation

* Deployment scripts and screencast (25%)
* Acceptance testing (40%)
* Exploratory Testing and Code Inspection (30%)
* Bonus: Continuous Integration Service (20%)