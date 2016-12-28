# Features

- Split nomad job into nomad-server + nomad-client jobs.
- Added BOSH v2 links. nomad-server provides the nomad_servers properties for other servers and nomad-client jobs to find each other without addional config.
- Added nomad.docker.cleanup_image and nomad.leave_on_terminate properties.
- Added templates/v2/*.yml files to use with cloud-config type deployments.
