# Docker for Beginners — docker-curriculum.com

[Tutorial](https://docker-curriculum.com/) · **Author:** Prakhar Srivastav · **Status:** completed (2024) · [Tutorial code (GitHub)](https://github.com/prakhar1989/docker-curriculum)

## About

A free, hands-on tutorial: run containers, build images, deploy web apps, then run a multi-container app with Docker Compose. It also deploys the apps to AWS.

**Docker** packages an app with all its dependencies into a **container**. A container shares the kernel of the host (usually Linux), so it is much lighter than a virtual machine but still isolated. The same container runs the same way on a laptop, in a data center or in the cloud.

## Course content

| # | Section | Topics |
|---|---|---|
| 1 | Introduction | What containers are, containers vs virtual machines |
| 2 | Getting Started | Install Docker |
| 3 | Hello World | Run a first container (busybox), `docker run`, `docker ps` |
| 4 | Webapps with Docker | Static website, images, Dockerfile, deploy to AWS Elastic Beanstalk |
| 5 | Multi Container Environments | App + database, Docker networks, Docker Compose, deploy to AWS ECS |
| 6 | Conclusion | Next steps |

## My notes

My commands, networking notes and templates (Dockerfile, Compose) are in my cheat sheets: [devops_cheat_sheets/docker](https://github.com/PoissonChevre/devops_cheat_sheets/tree/main/docker)

## Resources

**Official docs**

- [Docker documentation](https://docs.docker.com/)
- [Docker Desktop with the WSL 2 backend (Windows)](https://docs.docker.com/desktop/wsl/)

**Videos**

- TechWorld with Nana: [Docker Crash Course (1 hour)](https://www.youtube.com/watch?v=pg19Z8LL06w) · [Docker Tutorial for Beginners (3 hours)](https://www.youtube.com/watch?v=3c-iBn73dDE) · [Ultimate Docker Compose Tutorial](https://www.youtube.com/watch?v=SXwC9fSwct8)
- NetworkChuck: [Docker networking is CRAZY!!](https://www.youtube.com/watch?v=bKFMS5C4CG0)
- Christian Lempa: [Docker Networking Tutorial, all network types explained](https://www.youtube.com/watch?v=5grbXvV_DSk)

**Cheat sheets and articles**

- [Docker commands cheat sheet (Spacelift)](https://spacelift.io/blog/docker-commands-cheat-sheet)
- [Docker cheat sheet (GitHub)](https://github.com/wsargent/docker-cheat-sheet)
- [Docker Network, Part 2 (Medium)](https://linumary.medium.com/docker-network-part-2-5d02e4e95ac6)
