# Pillar Card Releases

This repository contains the production releases of the Pillar dashboard cards.

## Purpose

This repository is automatically updated by GitHub Actions from the private `pillar-cards` source repository.

It contains only production artifacts used for deployment and updates.

## Contents

- Production JavaScript bundles
- Release ZIP packages
- Version manifests
- Checksums

It does **not** contain the source code.

## For Home Assistant

The Pillar Manager Home Assistant add-on checks this repository for new releases and installs updates automatically.

## Release Process

1. Development occurs in the private `pillar-cards` repository.
2. A GitHub Release is created.
3. GitHub Actions build the production package.
4. The release artifacts are published to this repository automatically.

No manual changes should be made to this repository.