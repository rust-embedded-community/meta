# Instructions for Crate Transfer

This document outlines the necessary steps to transfer a project to the rust-embedded-community
project.

Users that are interested in their transfer can retain original ownership and write-control to any
projects that they wish to transfer as well.

## Process

The process for transferring ownership depends on whether or not the original crate owner would like
to join the `rust-embedded-community` project.

### Transfer Process (Joining the R-E-C)

This process is used if the original crate owner would like to become a member of the
`rust-embedded-community` project.

1. Request to join the community by following the steps outlined [here](README.md#joining-the-community).
1. Once you have been added, request to transfer the repository under the repository settings:
    1. Navigate to transfer the repository under the repository settings.
    `https://github.com/<YOUR-ORG>/<YOUR-REPO>/settings`: General > Danger Zone > "Transfer
    ownership"
    2. Select "Specify an organization or username" and supply `rust-embedded-community`
    3. Confirm the transfer and select "I understand, transfer this repository"

2. Add the rust-embedded-community project to the crates.io owners to allow the community
   to issue updated releases for the crate:
   ```sh
   cargo owner --add github:rust-embedded-community:all
   ```

### Transfer Process (Without Joining)

The following process can be used if the original crate owner does not wish to join the
`rust-embedded-community`.

1. Request to transfer the repository under the repository settings:
    1. Navigate to transfer the repository under the repository settings.
    `https://github.com/<YOUR-ORG>/<YOUR-REPO>/settings`: General > Danger Zone > "Transfer
    ownership"
    2. Select "Specify an organization or username" and supply the Github username of one of the
       `rust-embedded-community` members that you have been previously in contact with about
       transferring the repository.
        * If you haven't been in contact with anyone yet, feel free to [open an issue](https://github.com/rust-embedded-community/meta/issues/new) and one of us will be
        happy to assist.
    3. Confirm the transfer and select "I understand, transfer this repository"
    4. Add the contact person to the crates.io owners to allow them to allow the community
     to issue updated releases for the crate:
   ```sh
   cargo owner --add <MEMBER-GITHUB-ID>
   ```

Once the repository is transferred to the organizational member, that member should follow the steps
outlined above for transferring to the `rust-embedded-comunity`.
