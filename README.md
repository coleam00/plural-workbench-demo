# plural-workbench-demo

GitOps repo for a small demo environment managed by [Plural](https://plural.sh).

| Service | What it is |
|---|---|
| `payments-api` | Tiny Python HTTP service that needs `DATABASE_URL` at boot |
| `storefront` | nginx front end |

Manifests live under `k8s/` and are deployed to the `plural-demo` cluster by a Plural `ServiceDeployment`.
