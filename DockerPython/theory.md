## Dockerfile Breakdown with Comments

Here is a breakdown of each line in your Dockerfile with comments explaining their purpose and function :

| \*\*Line | Command | Explanation\*\* |
| -------- | ------- | --------------- |

Dockerfile

```
FROM python:<version>` | Defines the base image upon which your container will be built in this case using the official Python image with the specified version (here `python:<version>` represents the desired version like `python:<version>`).
```

Dockerfile

```
WORKDIR /app | Sets the working directory inside the container to `/app`. This is where your application files will be located when the container starts and where commands like `CMD ` or `ENTRYPOINT ` will be executed from by default
```

Dockerfile

```
COPY requirements
```
