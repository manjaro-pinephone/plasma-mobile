# Manjaro Plasma-Mobile
[![iso_build](https://github.com/manjaro-pinephone/plasma-mobile/workflows/image_build/badge.svg)](https://github.com/manjaro-pinephone/plasma-mobile/actions)

## Description

Plasma-Mobile of Manjaro Linux for the Pinephone

## Where can I download an ISO image?

Images are built and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-pinephone/plasma-mobile/releases).

## Sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## Building

Step 1. Check out the arm-profiles.
Step 2. Run the the following command `sudo buildarmimg -d pinephone -e plasma-mobile -v $DATE -b unstable -k plasma-mobile`