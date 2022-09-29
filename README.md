# Solution to akash-task
DevOps Hiring Task for Akash


* Clone this repo, create a branch, and make all your changes in the branch
	- The repo was well cloned, then a branch (devops) was created successfully and all changes where made in the new branch
* Follow the instructions [here](https://docs.akash.network/guides/deploy) to download and  setup [CloudMos](https://cloudmos.io/) on your computer
	-the instruction to download and setup a wallet was done successfully with keplr
	-The desktop setup for [CloudMos](https://cloudmos.io/) on my computer was swift following the Docmentation stepwisely
* Share your wallet address on Basecamp so you can receive some tokens.
	- My wallet address akash152myjv0t4xvkc8v5ecn9d8fe0jm6r7jl0x7u8f was generated from keplr extension on my chrome and 10AKT token was deposited to it after sharing
* Deploy the [App](../akash-task/app/) folder to Akash
	- The App deployment process was done in three (3) phases which are;
	- 1: Isolated environmrnt
	- This was to test if the app was working locally on my Virtual machine (Ubuntu) using some dependencies like Nodejs16, nginx, and yarn for the local deployment
	- 2: On Docker (container)
	- This was followed by the document shared on akash deployment so as to generate docker image using my Dockerfile and .dockerignore
	- 3: On CloudMos platform (Akashnalytic)
	- After generating the docker image which was pushed to my DockerHun Repository, following the medium resarch link [here](https://medium.com/@figuregang/developing-deploying-on-akash-7aecd5d9d467)
	- Then i generated a tag for the image which i used for the SDL script deplo.yml for the deployment on akash using an empty template to fill the SDL.
* share a working link to the hosted project.
	- Here is the [link](http://01mbjcj9chckldtd7f8g6ovpes.ingress.d3akash.cloud/) to the hosted project
* Contact us if any issues come up.
	- I did with 0iclid on basecamp and he did help me with SDL yamlfile
* Once done add the setup files and docker images, as well as setup instructions to the branch and make a PR
	- Okay, Check the [app folder](Sir-Kush/akash-task/app) for the setup files and docker image as well as the setup instructions
* Upon completion, write an explanation on how you got the project hosted, and share your challenges.
	- Okay, check the [here](Sir-Kush/akash-task/challenges.txt)

## Seeking Help

* If you need any help, you can check with us on Basecamp,  the Akash [Docs](https://docs.akash.network/) as well as both [their's](https://discord.com/invite/akash) and [CloudMos'](https://discord.gg/rXDFNYnFwv) Discord servers
* Remember to always be polite, to describe clearly what problems your ar having, what you've done, and how you attempted to solve it.
* Make sure you've already tried solving the problem by going through the normal channels (docs, Google, StackOverflow) before asking for help.

