# Good Docker Resources

This is a list of good Docker resources I found on web. Most of these are discovered using Docker weekly newsletters.

1. ​:memo: [ENTRYPOINT vs CMD: Back to Basics](http://www.johnzaccone.io/entrypoint-vs-cmd-back-to-basics/): A good blog that explains difference between two common Dockerfile commands. An in-depth to the point post. 
2. ​:memo: [Linux Docker base images](https://sreeninet.wordpress.com/2017/05/13/linux-docker-base-images/): This blogs talks about how you can create your own linux base images using `mkimage.sh` file.
3. :memo:[Protect Sensitive Data in Docker](https://davidwalsh.name/docker-compose-override): This post recommends using `docker-compose.override.yml` file for storing sensitive information. Make sure to add `docker-compose.override.yml` in your version control ignore file. Useful tip.
4. ​:video_camera: [Escape From Your VMs with Image2Docker](https://www.youtube.com/watch?v=YVfiK72Il5A&t=2813s): This DockerCon 2017 video talk about Image2Docker tool that can be used to write a Dockerfile from a VM. It is lift and shift tool. There are two versions of it — one for windows and other for linux.
5. ​:memo: [Raft logs on Swarm mode](https://medium.com/lucjuggery/raft-logs-on-swarm-mode-1351eff1e690): This lengthy post talks how Docker Swarm works under the hood. 
6. ​:memo:​ [Using Docker secrets during development](https://blog.mikesir87.io/2017/05/using-docker-secrets-during-development/): This is a very good post that shows how you can use secrets for your local development. It shows how you can use docker-compose to inject secrets without depending on environment variables.


## Legends

* ​:memo: - a text resource — blog/article/tutorial
* ​:video_camera: - a video resource 