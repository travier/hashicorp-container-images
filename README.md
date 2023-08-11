# Archived as Hashicorp projects are no longer open source

See https://www.hashicorp.com/blog/hashicorp-adopts-business-source-license

Original README below.

---

# Containerfiles for Hashicorp projects

Those containers are built using GitHub Actions and hosted on Quay.io.
Each `Containerfile` is in a specific folder in this repo.

All repositories are under the [travier](https://quay.io/user/travier)
namespace.

| Quay.io repository | Description |
|-|-|
| [nomad](https://quay.io/repository/travier/nomad) | [Nomad](https://www.nomadproject.io/) with [podman driver](https://github.com/hashicorp/nomad-driver-podman) (binaries only) |
| [nomad-fedora](https://quay.io/repository/travier/nomad-fedora) | [Nomad](https://www.nomadproject.io/) with [podman driver](https://github.com/hashicorp/nomad-driver-podman), based on Fedora's container image (binaries and dependencies) |
| [consul](https://quay.io/repository/travier/consul) | [consult](https://www.consul.io/) (binary only) |
| [vault](https://quay.io/repository/travier/vault) | [vault](https://www.vaultproject.io/) (binary only) |

## License

See [LICENSE](LICENSE).
