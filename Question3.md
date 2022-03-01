**MULTI STAGE BUILDS:**

In multi stage builds we use multiple FROM statements in docker file.

Artifacts from previous stage can be copied from previous stages leaving behind everything we dont need in the final image.

Final image is build on the basis of last FROM command.

