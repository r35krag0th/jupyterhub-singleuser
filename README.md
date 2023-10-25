# JupyterHub Single User with Build Essential

This is just [singleuser-sample](https://github.com/jupyterhub/zero-to-jupyterhub-k8s/tree/main/images/singleuser-sample)
with the `buildessential` package added.

**Normally** you wouldn't want to compile dependencies in the container, but I've run into cases
where the wheel isn't available.

This is just a lazy solution that accomplishes the objective.
