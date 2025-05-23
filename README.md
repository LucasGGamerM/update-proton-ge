[![Build status on GitLab CI][gitlab-ci-master-badge]][gitlab-ci-link]

[gitlab-ci-link]: https://gitlab.com/timvisee/update-proton-ge/pipelines
[gitlab-ci-master-badge]: https://gitlab.com/timvisee/update-proton-ge/badges/master/pipeline.svg

# Update Proton GloriousEggroll script
A script to update your [Proton GloriousEggroll][proton-ge] installation to the latest
version, so you don't have to do it yourself. Also makes a symlink to the latest version.

## Usage
Please refer to the Proton GloriousEggroll installation instructions first to
make sure you meet all requirements:

https://github.com/GloriousEggroll/proton-ge-custom#installation

To use this script, download it first (and make it executable):

```bash
wget https://raw.githubusercontent.com/LucasGGamerM/update-proton-ge/refs/heads/master/update-proton-ge
chmod a+x ./update-proton-ge
```

Then run it to install the latest version of GloriousEggroll's Proton:

```bash
./update-proton-ge

# Found latest version: 5.9-GE-8-ST
# Downloading...
# /tmp/Proton-5.9-GE-8-ST.t 100%[======>] 390,79M  4,11MB/s    in 2m 2s
# Installing...
# Cleanup...
# Installation complete
```

## License
This project is released under the MIT license.
Check out the [LICENSE](LICENSE) file for more information.

[proton-ge]: https://github.com/GloriousEggroll/proton-ge-custom
