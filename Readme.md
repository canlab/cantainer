===== Docker Working Group Notes =====

For now, we should use docker, since it's already the standard. We can switch to singularity later
if we need to.

==== Making a docker container with the matlab runtime ====

===Warning! I have not actually tried this! ===

1. Wrap the function so that it only takes string inputs.
2. Compile the function with the matlab compiler.
3. Install a docker image with the matlab compiler runtime, and (to test) run the image inside it.
4. Post on docker hub.
