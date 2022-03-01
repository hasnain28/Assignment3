**RUN:**

Run command is an image build step command.

After executing this command possibly a new image is found which will become the base of container eventually.

**CMD:**

It is a run type command.

Can be changed at run time as well.

It specifies what command need to be run by default while launching the container.

**ENTRYPOINT:**

It is also a run time command.

It is the first command to be executed by default while launching the container.

If entry point is not defined CMD becomes the default command.

If both CMD and entry point are defined CMD is passed as an argument to entrypoint.
 