# containers
Docker containers for general use

On push to `main`, the `ros-core` image is build and pushed to Github Container Registry.

## Pulling the images

Example:
```
docker pull ghcr.io/high-flyers/ros-core:latest
```

### Authenticating to Github Container Registry
You have to do this only once.

1. Create a Personal Access Token - [guide](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic)
2. Login to `ghcr.io` with the access token - [guide](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry#authenticating-with-a-personal-access-token-classic)
