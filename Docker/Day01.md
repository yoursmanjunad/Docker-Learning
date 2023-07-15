
# DevOps Learning   

 **Day - 01**

What is Docker? 

Docker is a tool which is used to containerize the applications and run them in a isolated environment which is better than the environment provided by the Virtual Machines. 

Let us take an instance that, developers are familiar with the sound `it works on my Machines` - it means their application may not work on other's machine. But ever thought that why it happens? 

While developing the applications, developers use several dependencies, versions and OS. These are installed in the developer's end and they work on it and run their application successfully. 

But when they send their code to others and running that application, there are chances it may not work. Because, there would be several reasons like 
 * Missing dependencies,
 * Different versions of Framework or languages,
 * Different Operating System, etc. 
You get the idea. 

So, to not to raise this situation, what docker helps that it creates an Image of the application, which can be pulled and able to run the application on any machine using Docker. 

What is an Image?

Image is a file used to run the application in a container. This image built using the file called `Dockerfile` in which we mention the Operating System, Versions of the fameworks or Languages we work on, Dependencines, essential commands to run the application etc in a order using  `YAML` language.

Using a docker command, we can build the application's Image and push it to the DockerHub. So common users(using public registry) or Team members (Private registry) can pull this image and run on their machines using docker  easily. 

Why containers? 

In Virtual Machines, the environment makes it so worse as compared to the Containers. Like 
* VMs takes more time to start
* It is Slower
* Contains multiple host OS
* less efficient than real machines because they access hardware indirectly
* Running multiple VMs on one physical host can result in unstable performance
* If the physical server crashes, all of the applications running on it will go down. 

So, to overcome all these problems docker containers helps us. 

* Containers are Weightless, 
* Takes minimal time to start
* Runs on host server's kernel
* It is more efficient
* Running multiple containers didn't show much effect on server's health, and so on...

`Docker helps us to create a container and run those images in a container.`

Visit [Referece - Containers vs VM](https://www.networkworld.com/article/3583508/what-is-a-virtual-machine-and-why-are-they-so-useful.html)



