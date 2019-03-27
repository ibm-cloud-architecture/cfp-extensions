# IBM Cloud Private - Cloud Foundry Extensions Index
This repository is a starting point for IBM created extensions for your Cloud Foundry deployment. These Extensions
enable features and integrations, that allow you to tailor the offering to your enterprise's needs.

# Featured Repositories
- Enable Cloud Foundry to use external database sources, [cfp-cf-ext-db-extension](https://github.com/ibm-cloud-architecture/cfp-cf-ext-db-extension)
- Enable AWS S3 Objectstorage for Cloud Foundry, [cfp-s3-blobstore-extension](https://github.com/ibm-cloud-architecture/cfp-s3-blobstore-extension)


---

### How to update the extensions in this repository
1. Optional if you get a working set error. Make sure all changes are already committed
```
git reset --hard
```
2. Pull in the lastest subtree from branch `master`
```
git subtree pull --prefix=REPOSITORY_NAME https://github.com/ibm-cloud-architecture/REPOSITORY_NAME master --squash
```
3. Push the change to the remote repository
