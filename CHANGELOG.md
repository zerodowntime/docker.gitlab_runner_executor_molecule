# History

## 1.6.1 (Jan 27, 2021)

- Setup base git directories

## 1.6.0 (Dec 21, 2020)

- Dropped vagrant and libvirt
- Migrated image to use docker in docker
- From now onward base image is alpine
- Bumped molecule to 3.2.x

## 1.5.2 (Sept 10, 2020)

- Updated vagrant version to 2.2.9

## 1.5.1 (Sept 10, 2020)

- Adding missing ltdl library to Docker image

## 1.5.0 (March 8, 2020)

- Dropped python2 in favour of python3
- Cleaned Dockerfile
- Bumped molecule from `2.22` to `3.x`
- Following molecule, change in policy to manage ansible N/N-1 versions, instead of N/N-1/N-2 as before. Currently the oldest supported ansible is 2.8.0
- To not override old images, the only maintained format of images is `ansible-[ansible_version]-molecule-[molecule_version]`

## 1.4.2 (March 7, 2020)

- Added vim to image
- Updated molecule in dockerfile
- Removed debug from ansible default
- Dropped ansible 2.6 for 2.9
- Bumped vagrant version

## 1.4.1 (Sept 9, 2019)

- updated molecule `2.20.02`->`2.22`
- changed support for ansible from patch versions to minors

## 1.4.0 (Jul 24, 2019)

- updated molecule `2.20.0`->`2.20.2`
- updated vagrant `2.2.3`->`2.2.2`
- updated ansible `2.8+`

## 1.3.0 (May 17, 2019)

Important Note:

`Since now images are tagged via ansible and molecule version: ansible-ansible_version-molecule-molecule_version. Old format that is tagging via only ansible - ansible-ansible_version is maintained but may become deprecated in future releases`

Other changes:

- Removed hooks
- Added local builds with Makefile in place of hooks
- Added changelog
- Updated defaults in Dockerfile

## 1.2.0 (Apr 4, 2019)

- Updated molecule to new version 2.20
- Changes in image - update of setuptools - forced by new molecule
- Added new versions

## 1.1.0 (Feb 28, 2019)

- Fixed issue where envs should be args
- Added ansible.cfg for docker image
- Changed name of the image

## 1.0.0 (Feb 21, 2019)

- initial release

<!-- ### Backwards Incompatibilities / Notes -->

<!-- ### Important Changes -->

<!-- ### Others -->

<!-- ### Bug Fixes -->

<!-- ### Known Issues -->
