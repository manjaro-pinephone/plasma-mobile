# Manjaro Plasma-Mobile
[![iso_build](https://github.com/manjaro-pinephone/plasma-mobile/workflows/image_build/badge.svg)](https://github.com/manjaro-pinephone/plasma-mobile/actions)

## description

Plasma-Mobile of Manjaro Linux for the Pinephone

## where can I download an iso?

Images are built and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-pinephone/plasma-mobile/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d pinephone -e plasma-mobile -v $DATE -b unstable -k plasma-mobile`
