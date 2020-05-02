# Step 1

## About this 'test'

The purpose of this test is to know more about each candidate to our Managed Services and DevOps Engineer position at NubeliU. This is not a test which aims at generating a score or an assertive rate, and rather a study case to learn more about your knowledges, experience and the way that you work. Feel free to code your solution to the problem that we are proposing and if have any question, please, let we know by email: rh@nubeliu.com.

## Scenario

Inside of the `app` directory there is a very simple Flask application. When this app starts it will read an environment variable called `NUB_PASS` that will be the API password. Then, a call to the application needs a `Header` of `Authorization` with a specific token. Eg: `curl -H "Authorization: Token VALUE_OF_NUB_PASS_VAR " http://localhost/`. You should tell us how to define/change this token in an easy way.

Your goal is to deploy this application in a public cloud (AWS, GCP or Azure) using some kind of Continuous Integration tool and/or cloud provider's DevOps tools. For this specific task it is enought to us to have a YOUR_PREFERED_CI_TOOL.yml or related file(s) commited to this repository.

Probably, you'll need to create a free-tier cloud account, or use an already created account, but don't worry about it. We won't look at your account or call the application already running. We want that you show us how to recreate all this infrastructure in our account as simply and less expensive as possible. Be creative. Create a part1.md file describing all the steps to deploy your stack in our environment. Be careful with the following points:

* You should start in a totally new AWS account.
* This application need to be into a Docker container.

Feel free to change the code of the application if you need it.

# Step 2

## About this 'test'

This test aims at understanding your knowledge about cloud and DevOps scenarios. We want to know if you know these subjects, tools and how cloud products and tools talk one with each other.

## Scenario

Look at the following image, create a `part2.md` file with the technical description about this topology.

![aws-test-scenario](https://user-images.githubusercontent.com/29125605/29424258-5d7d5c2a-8355-11e7-9701-2fb26621b6b0.png)

# Ship it! 

* You should clone this repo and commit all your changes, but **don't** open a pull request or leave your code visible to the world just like in a fork for example.
* When you finish it, compact all the directory and send it to us. **We wanna see your commits, don't forget the `.git` directory.**
* The more verbose you'll be in git commits, the better. **We wanna follow your steps.**
* Send an email to rh@nubeliu.com with your compacted file.

Good coding and good luck!
