<p align="center">
  <img src="./images/prisma-cloud-logo.png" alt="spring-logo" height="150" width="150">
  <h1 align="center">Prisma Cloud Policy Updates</h1>
</p>
<p align="center" style="font-size: 1.2rem;">Get notified of policy changes coming in Prisma Cloud releases</p>

![Prisma Cloud 20.11.2](https://img.shields.io/badge/Prisma%20Cloud-20.11.2-blue)
![Latest release Oct 29, 2020](https://img.shields.io/badge/Latest%20release-Oct%2029%2C%202020-brightgreen) 

## Overview

The JSON files in this repo contain new and updated policies planned for the
upcoming release. The JSON files have the policy metadata, remediation, and RQL
information.

Each JSON block represents a policy, the JSON fields with the suffix "_updated"
represents the updated value for the field in the updated policy.

## Notifications

To get notified of new policy changes, at the top right corner of GitHub select
**Watch** -> **Releases only**

<p align="center"><img src="./images/releases-only.png" alt="watch -> releases only" /></p>


## Notes

* The release notice currently includes only RQL based policies (Config, Network, and Audit Event policies). Other policy types (Anomaly, Data, Build) are not included. 
* Saved searches not part of default policies are currently not included.
* Compliance changes are currently not included.

*The JSON files contain custom data fields in addition to the data from the Prisma Cloud Policy and Search Manager API endpoints*