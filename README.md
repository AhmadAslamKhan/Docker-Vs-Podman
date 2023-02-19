# Docker-Vs-Podman

Docker came in with a whole new system of containerization and rapidly grew popular and widely used system among everyone.

but is docker the only containerization system? if not is there any other tool that can match or even surpass docker?

well podman was made with the concept in mind that it was "made to replace docker". At least that's what the Red Hat Linux claimed. But is it better? or is docker still better?

This article is all about informing you what docker and podman are. But most importantly which one is better and why.

# What is Docker?

Docker is a platform for creating, deploying and managing containers. Docker can work across all platforms making it really usefull and due to its simplicity it has also been really popular.

# What is Podman?

Podman was created by Red Hat . It is a daemonless, rootless container engine made to become a replacement of docker. Initially it was only going to be a debugging tool before becoming a potential replacement of docker.

# Dockers Vs Podman?

Docker and Podman, both are containerization tools which you can use to start, deploy and manage containers. Both have their own pros and cons.

we cant really decide which one is better than the other or how both compare and compete with one another without discussing their indivisual pros and cons.

# Docker Pros & Cons:

# Docker Pros:

Docker is very simple and flexible. docker was made so that it is easy to use and work with.

# Docker Cons:

As we know docker works on a daemon based system and as the daemon process runs with root privilege's this tends to create security threat. thus docker is not considered comparatively safe.

# Podman Pros & Cons:

# Podman Pros:

Podman is a daemonless architecture thus making it more secure than dockers.

Podman can do rootless operations without the root privileges.

# Podman Cons:

Podman has limited featured. Thus it has to rely on other programs like buildah. It also does not support docker-swarm. so podman has to work with other programs to provide many features.

# So which one to use?

Well as we can see, both of them have their own pros and cons, one might work as a whole package while other might need some tools to do the same thing but one provides a better secure environment whole one does not.

so the real question is not which one is better, but which one is to be used when?

# so the real question is not which one is better, but which one is to be used when?

As docker was designed to be simple, it is easy to learn and one can become used to it relatively faster. Plus it is like a complete package in comparison as it contains most of the tools needed while using containers.

As docker came a few years before podman you are more likely to see people or their work done on docker.

so if you value the things mentioned above its best if you go with docker for your work.

# When to use podman?

As podman is daemonless it provides a better security compaered to docker.

Podman is light program as it focuses mainly on running, deploying and managing containers, you can do additional functionalities with supported tools. This was only the tools/functionalities you need take up your space. this gives you more control and freedom.

# Conclusion:

Now that you have seen the comparison, the pros and cons, and the general usage details of both dockers and podman, you are more than capable to decide whether to go for docker or podman depending upon your work needs.
