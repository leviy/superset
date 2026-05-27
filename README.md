# Leviy's integration branch

This is a branch for integrating the work of the team members. The integration
branch is used to merge the work of the team members into a single branch. This
branch is used to ensure that the work of the team members is integrated
correctly and that the project is working as expected.

## Build a working docker image
```shell
docker build -t ghcr.io/leviy/superset:<base-version: 4.1.1><tag-name> .

# Example
docker build -t ghcr.io/leviy/superset:4.1.1-current-translations .
```

Push to the repository
```shell
docker push ghcr.io/leviy/superset:<base-version: 4.1.1><tag-name>
```

Use the new image as the base of the Dockerfile in analytics repository.
