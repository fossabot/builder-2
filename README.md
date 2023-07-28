[![UBI 8 multi-arch image build](https://github.com/konveyor/builder/actions/workflows/ubi8_multi_arch_image_build.yml/badge.svg)](https://github.com/konveyor/builder/actions/workflows/ubi8_multi_arch_image_build.yml)
[![UBI 9 multi-arch image build](https://github.com/konveyor/builder/actions/workflows/ubi9_multi_arch_image_build.yml/badge.svg)](https://github.com/konveyor/builder/actions/workflows/ubi9_multi_arch_image_build.yml)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Fbuilder.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Fbuilder?ref=badge_shield)

# Builder
From time to time we need a newer version of Go to build projects than is available from go-toolset, or other images available on Quay or registry.access.redhat.com.

While there are usually up to date images on docker.io we tend to hit frequent issues with rate limiting when pulling from there to build on Quay.

This Dockerfile can be used to build an updated image if necessary.

To see the most recent version of Go for EL8:  
https://vault.centos.org/centos/8-stream/AppStream/Source/SPackages/  
  
To see the most recent version of Go for EL9:  
http://mirror.stream.centos.org/9-stream/AppStream/source/tree/

## Code of Conduct
Refer to Konveyor's Code of Conduct [here](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md).


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Fbuilder.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Fbuilder?ref=badge_large)