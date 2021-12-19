# README

Small script that alleviates some of the security concerns with running `curl <url> | sh -`.

## Usage

Assuming the site provides it, the md5sum can be used to verify the downloaded script before running as such:

`curl <url> | inline-md5sum <md5sum> | sh -`
