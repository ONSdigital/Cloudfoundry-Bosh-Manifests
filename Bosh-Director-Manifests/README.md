# Bosh Manifests for `bosh create-env`

It should be possible to have a single Bosh manifest and have them adjusted to handle various CPIs via a Bosh operations file, but this makes the files a little more complicated to read.

Once more CPIs have been added the choice may be taken to go to a single manifest and CPI specific Bosh operations files, but as there is only AWS and vSphere (in progress), there is little point in generalising.
