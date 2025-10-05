### Docker Image

- Recipe card for your software
- Includes all the necessary ingredients (code, configuration, etc) to make the software work
- can be built and shared easily

⇒ check image ⇒ docker image

### Docker Container

- Now That you have your recipe, you can create as many containers as you want
- each holding an instance of your softeware
- they share the some core recipe(docker image) but can have different setting or data
- A way to package an application with all the necessary dependencies and configuration.
- it can be easily shared.
- Makes deployment and development efficient,

### Docker Architacture

![Screenshot from 2024-10-13 20-33-17.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ef9c962e-3b4b-4ceb-adf7-9db20221cb08/5b421e1e-3dd3-4ab6-a59e-3b6fa60f99fb/Screenshot_from_2024-10-13_20-33-17.png)

### Docker Vs VMs

**Docker**

- Low impact on OS, very fast, low disk space usage.
- Sharing, re-building, and distribution are easy
- Encapsulate apps instead of the whole machine.

**VMs**

- High impact on OS, Slower high disk space usage.
- Sharing re-building and distribution is challenging.
- Encapsulate the whole machine.

### Main Components of Docker

- Docker File
- Docker Image
- Docker Container
- Docker Registry
