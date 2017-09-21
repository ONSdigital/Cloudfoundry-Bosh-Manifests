# Bosh, Cloudfoundry, Manifests

Series of Bosh manifests to create a Cloudfoundry installation

- Bosh-Lite-Manifests
  - Bosh-Template.yml
    - This contains the manifest require to create an initial Bosh environment (eg bosh create-env)
  - Bosh-static-ips.yml
    - List of static/reserved IPs

- Bosh-Full-Manifests
  - Bosh-Template-AWS-CloudConfig.yml
    - AWS CPI manifest, single AZ
  - Bosh-Template-AWS-CloudConfig-MultiAZ.yml
    - AWS CPI manifest, multi AZ

  - Bosh-Template-preamble.yml
    - Initial manifest to create databases

  - Bosh-Template.yml
    - Cloudfoundry manifest, single AZ
  - Bosh-Template-MultiAZ.yml
    - Cloudfoundry manifest, single AZ

  - Bosh-static-ips.yml
    - List of static/reserved IPs
