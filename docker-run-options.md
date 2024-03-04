# Docker Run Options

When running a Docker container, you can use various options to customize its behavior. Here are some common options that can be used with the `docker run` command:

1. `-d, --detach`: Run the container in detached mode (in the background).
2. `-i, --interactive`: Keep STDIN open even if not attached.
3. `-t, --tty`: Allocate a pseudo-TTY (terminal) for the container.
4. `--name`: Assign a name to the container.
5. `--rm`: Automatically remove the container when it exits.
6. `-e, --env`: Set environment variables inside the container.
7. `-p, --publish`: Publish container's ports to the host.
8. `-v, --volume`: Bind mount a volume from the host into the container.
9. `--network`: Connect the container to a specific Docker network.
10. `--restart`: Restart policy for the container.
11. `--privileged`: Give extended privileges to the container.
12. `--user`: Set the username or UID for the container's entry point process.
13. `--entrypoint`: Override the default entry point of the container.
14. `--workdir`: Set the working directory inside the container.
15. `--memory`: Set the memory limit for the container.
16. `--cpu`: Set the CPU shares (relative weight) for the container.
17. `--hostname`: Set the hostname of the container.
18. `--expose`: Expose a port or a range of ports from the container.
19. `--env-file`: Read environment variables from a file and set them in the container.
20. `--label`: Add metadata to the container in the form of key-value pairs.

These are just some of the common options. You can find a complete list of options and their descriptions by running `docker run --help` or by referring to the Docker documentation.
