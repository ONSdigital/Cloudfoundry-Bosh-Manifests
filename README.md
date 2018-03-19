# Bosh, Cloudfoundry, Manifests

Series of Bosh manifests to create a Cloudfoundry installation

- Bosh-Director-Manifests
  - Bosh-Template-AWS.yml
    - This contains the manifest require to create an initial Bosh environment (eg bosh create-env)
    - AWS specific
  - Bosh-Template-vSphere.yml
    - This contains the manifest require to create an initial Bosh environment (eg bosh create-env)
    - vSphere specific
  - Bosh-static-ips.yml
    - List of static/reserved IPs

- Bosh-Full-Manifests
  - Bosh-Template-AWS-CloudConfig.yml
    - AWS CPI manifest, single AZ
  - Bosh-Template-AWS-CloudConfig-MultiAZ.yml
    - AWS CPI manifest, multi AZ
  - Bosh-Template-vSphere-CloudConfig.yml
    - vSphere CPI manifest, single AZ

  - Bosh-Template-preamble.yml
    - Initial manifest to create databases

  - Bosh-Template.yml
    - Cloudfoundry manifest, single AZ, no HA
  - Bosh-Template-HA.yml
    - Cloudfoundry manifest, single AZ, HA
  - Bosh-Template-MultiAZ.yml
    - Cloudfoundry manifest, single AZ

  - Bosh-static-ips.yml
    - List of static/reserved IPs (singleAZ)
  - Bosh-static-ips-HA.yml
    - List of static/reserved IPs (singleAZ + HA)
  - Bosh-static-ips-multiAZ.yml
    - List of static/reserved IPs (multiAZ)
