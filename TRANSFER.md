# Instructions for Crate Transfer

This document outlines the necessary steps to transfer a project to the rust-embedded-community
project.

Users that are interested in their transfer can retain original ownership and write-control to any
projects that they wish to transfer as well.

## Process

1. Request to transfer the repository under the repository settings:
    1. Navigate to transfer the repository under the repository settings.
    `https://github.com/<YOUR-ORG>/<YOUR-REPO>/settings`: General > Danger Zone > "Transfer
    ownership"
    2. Select "Specify an organization or username" and supply `rust-embedded-community`
    3. Confirm the transfer and select "I understand, transfer this repository"

2. [Optional] Add the rust-embedded-community project to the crates.io owners to allow the community
   to issue updated releases for the crate:
   ```sh
   cargo owner --add github:rust-embedded-community:all
   ```

3. [Optional] Request to join the community if you want to retain access to your repository by
   following the steps outlined [here](README.md#joining-the-community).
