# gitea-runner-images
An image of the Gitea Actions Runner, upgraded with certificates from a local root CA.

You can find the images on [stvoigt/gitea-runner-images](https://hub.docker.com/r/stvoigt/gitea-runner-images).

This image is based on gitea's Official docker images that are used by [act_runner](https://gitea.com/gitea/act_runner) to run workflows.

See [gitea/runner-images](https://github.com/stvt/gitea-runner-images.git) and [catthehacker/docker_images](https://github.com/catthehacker/docker_images) to find out more about those projects.

## Image build process

Images are built from `gitea/runner-images:*`. An then the root CA certificate is injected.

As of 2024-09 only "default" type of image is built.

Maybe "slim" and "full" are added in the future.
