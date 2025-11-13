# OPEN UG LABS APT REPOSITORY

This Git Repository hosts and serves the APT repository for all packages published by the Open UG Labs Organisation.


## Quick Setup

Get started with our repository in just a few simple steps:

1. **Add Repository**
   
   Add the Open UG repository to your system's sources list:
   ```sh
   echo "deb [trusted=yes] https://apt.open.ug stable main" | sudo tee /etc/apt/sources.list.d/openug.list
   ```
2. **Update Package List**
   
   Refresh your package database to include our packages:
   ```sh
   sudo apt update
   ```
3. **Install Packages**
   
   You're all set! Install any package from the list below using `apt`.


## Hosted Packages

- [Conveyor CI](https://conveyor.open.ug/): The lightweight engine for building distributed CI/CD systems with ease.
  ```sh
  sudo apt install conveyor
  ```
