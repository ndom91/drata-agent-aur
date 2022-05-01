# Drata Agent

AUR package of the [Drata](https://drata.com/) agent to be installed on employee computers.

## 📦 Package

The AUR package itself is nothing but a simple repacking of their official debian release. For more details, please see the details in the `pkg/PKGBUILD`.

The `pkg` subdirectory contains the contents of the AUR package / repository (https://aur.archlinux.org/packages/drata-agent).

## 🚢 Updating

The `release.yml` Github Action checks every day if there are new releases via their official `drata/agent-releases` repository. If so, the runner will download the new release, adjust all the required fields in the `PKGBUILD` and generate a new `.SRCINFO` file and push the updated contents of the `pkg` subdirectory to the AUR. This ensures a smooth auto-update process, while also keeping a copy of the AUR repository here on Github.

## 📝 License

ISC
