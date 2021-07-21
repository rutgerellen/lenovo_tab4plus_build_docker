# lenovo_tab4plus_build_docker
docker compose for lineage ci/cd based build.

# Usage
sync the repo.  Go to lineagedocker and execute docker-compose up (all of this on linux of course)

# details

This docker-compose file and set of folders is based on https://github.com/lineageos4microg/docker-lineage-cicd where a complete CI/CD toolset for Lineage is maintained. The docker compose-compose file and folders in this repo are directed at the Lenovo Tab 4 10 +, and the associated directories point to a local copy of the work done by lukaspieper (the branches used for building are forks from his work see https://github.com/lukaspieper/android_device_lenovo_tb_x704f and https://forum.xda-developers.com/t/rom-unofficial-11-tb-x704f-l-lineageos-18-1-for-lenovo-tab4-10-plus.4270183/)

When using on windows/WSL you might need to resize your WSL main volume see: https://docs.microsoft.com/en-us/windows/wsl/compare-versions#expanding-the-size-of-your-wsl-2-virtual-hard-disk
