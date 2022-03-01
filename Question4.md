**IMAGE:**

Image are made up of series of layers one above the other and are immutable.

Image can be created from scratch or from some custom image or can be downloaded via any registry.But every image must have a base image(either scratch or some custom image)

Image is a snapshot of container that are then used as a base of container.

**Container:**

Container is a running instance of an image.

Container is created when we use the image name after a run command.

When a container is created a thin read write layer is added onto the image.

This layer exists as long as container exists.

Container can be started stopped and event deleted.

There could be multiple containers of same image and each one of them are in complete isolation.



