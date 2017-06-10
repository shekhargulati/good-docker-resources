# Good Docker Resources

This is a list of good Docker resources I found on web. Most of these are discovered via Docker weekly newsletters.

1. ​:memo: [ENTRYPOINT vs CMD: Back to Basics](http://www.johnzaccone.io/entrypoint-vs-cmd-back-to-basics/): A good blog that explains difference between two common Dockerfile commands. An in-depth to the point post. 

2. ​:memo: [Linux Docker base images](https://sreeninet.wordpress.com/2017/05/13/linux-docker-base-images/): This blogs talks about how you can create your own linux base images using `mkimage.sh` file.

3. :memo:[Protect Sensitive Data in Docker](https://davidwalsh.name/docker-compose-override): This post recommends using `docker-compose.override.yml` file for storing sensitive information. Make sure to add `docker-compose.override.yml` in your version control ignore file. Useful tip.

4. ​:video_camera: [Escape From Your VMs with Image2Docker](https://www.youtube.com/watch?v=YVfiK72Il5A&t=2813s): This DockerCon 2017 video talk about Image2Docker tool that can be used to write a Dockerfile from a VM. It is lift and shift tool. There are two versions of it — one for windows and other for linux.

5. ​:memo: [Raft logs on Swarm mode](https://medium.com/lucjuggery/raft-logs-on-swarm-mode-1351eff1e690): This lengthy post talks how Docker Swarm works under the hood. 

6. ​:memo: [Using Docker secrets during development](https://blog.mikesir87.io/2017/05/using-docker-secrets-during-development/): This is a very good post that shows how you can use secrets for your local development. It shows how you can use docker-compose to inject secrets without depending on environment variables.

7. ​:memo: [Deploy the Voting App on a Docker Swarm using Compose version 3](https://medium.com/lucjuggery/deploy-the-voting-apps-stack-on-a-docker-swarm-4390fd5eee4): This good post shows how to deploy an application built using multiple services (aka Microservices) to Docker swarm cluster using `docker stack` command and `docker-compose.yml` configuration file.

8. ​:memo: [Fully automated development environment with docker-compose](https://blog.maqpie.com/2017/02/22/fully-automated-development-environment-with-docker-compose/): This post shares how to setup local development environment with docker-compose. A Lot of useful tips like booting up specific services, `COMPOSE_PROJECT_NAME`, `build` option, etc. 

9. ​:memo: [Docker Compose v3.1 file format now supports Docker 1.13.1 Secret Management](http://collabnix.com/archives/2565): This post will teach you how to use Docker's secret management feature to create and inject secrets to services. The post does not cover one aspect. You can use secrets with local docker-compose secrets files rather than `docker secret create` command.

10. ​[:memo: Comparing Docker compose versions](https://sreeninet.wordpress.com/2017/03/28/comparing-docker-compose-versions/): This post does a very good job distinguishing different Docker compose versions. Also, it clarify difference between — compose, stack, and dab formats. 

11. ​:memo: [How docker stack deploy works?](https://github.com/moby/moby/issues/29676): A github issue detailing how `docker stack deploy —compose-file`  works.

12. ​:video_camera: [All the New Goodness of Docker Compose](https://www.youtube.com/watch?v=VU85e4t-YHY): This talk gives a good overview of new features introduced in Docker Compose file version 3.0.

13. ​:memo: [Modernizing Traditional Applications with Docker](http://www.valcolabs.com/2017/05/07/modernizing-traditional-applications-with-docker/): A good post covering path to modernise traditional applications(or MTA).

14. ​:memo: [Leveraging the dockerignore file to Create Smaller Images](https://blog.codeship.com/leveraging-the-dockerignore-file-to-create-smaller-images/): This is something that should be obvious to all of us but somehow we all forget to use it. We should use `.dockerignore` file to specify files that we don't want to be included in the image.

15. ​:memo:​ [Managing Secrets in Docker Swarm](https://semaphoreci.com/community/tutorials/managing-secrets-in-docker-swarm): An in-depth tutorial on how secret management works with Docker Swarm.

    ​


## Legends

* ​:memo: - a text resource — blog/article/tutorial
* ​:video_camera: - a video resource 
