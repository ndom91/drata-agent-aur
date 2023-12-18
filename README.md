<img align="right" src="https://images.drata.com/x3hoqyjm3c27/KGLjH0qbRqmQ3Y3YVlSgB/2bb6cb13b1c98c0bff90931cdb332922/drata-wordmark-black.svg" width="320" />

## `drata-agent`

![GitHub last commit](https://img.shields.io/github/last-commit/ndom91/drata-agent-aur)
[![AUR version](https://img.shields.io/aur/version/drata-agent)](https://aur.archlinux.org/packages/drata-agent)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ndom91/drata-agent-aur/aur-publish?label=aur-publish)](https://github.com/ndom91/drata-agent-aur/actions/workflows/release.yml)

AUR package of the [Drata](https://drata.com/) agent to be installed on employee computers.

## 📦 Package

The AUR package itself is nothing but a simple repacking of their official debian release. For more details, please see the details in the `pkg/PKGBUILD`.

The `pkg` subdirectory contains the contents of the AUR package / [repository](https://aur.archlinux.org/packages/drata-agent).

## 🚢 Updating

The [`release.yml`](https://github.com/ndom91/drata-agent-aur/blob/main/.github/workflows/release.yml) Github Action checks every day if there are new releases via their official `drata/agent-releases` repository. If so, the runner will download the new release, adjust all the required fields in the `PKGBUILD` and generate a new `.SRCINFO` file and push the updated contents of the `pkg` subdirectory to the AUR. This ensures a smooth auto-update process, while also keeping a copy of the AUR repository here on Github.

## 📝 License

ISC
