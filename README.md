# Blender - NetLinux Custom Build

Custom Blender 5.0.1 build for the [NetLinux APT repository](https://packages.netlinux.co.uk).

## Install

```bash
sudo apt update
sudo apt install blender
```

(Requires the NetLinux repository to be configured.)

## Patches

Custom patches go in the `patches/` directory. They are applied in alphabetical order against the Blender source tree during the CI build.

## Build

Automated via GitHub Actions on push to `main`. See `.github/workflows/release-deb.yml`.
