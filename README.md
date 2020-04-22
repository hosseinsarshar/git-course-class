[![Build status](https://dev.azure.com/azurefreecredit/inclass-failed-pipeline/_apis/build/status/inclass-failed-pipeline-test)](https://dev.azure.com/azurefreecredit/inclass-failed-pipeline/_build/latest?definitionId=8)

# Crash Course to Git

This repo is built by Hossein Sarshar for the [AISC MLOps Workshop](https://www.eventbrite.ca/e/premium-hands-on-workshop-ml-ops-cloud-for-successful-ml-products-tickets-71406154731?aff=lunch#). Should you have any questions, feel free to email me at hossein.sarshar@gmail.com or tweet me at [classicboyir](https://twitter.com/classicboyir).

The aim is to provide a step to step guide to the main concepts of Git necessary for every data scientist.

For full MLOps guide, please check my other repo focusing on building [CI/CD pipeline for you ML workloads](https://github.com/classicboyir/build-release-ci-cd).

To learn about building reproducible experiments, please check my other repo focusing on building [building reproducible experiments](https://github.com/classicboyir/exp-repro).

### How to use this repo:
1. Fork this repo into your GitHub account
1. Create a new build pipeline on Azure DevOps for Pull Request and connect it to your remote repo
1. Create a new branch
1. Apply a change
1. Create a Pull Request to the master branch
1. Check how the pipeline is kick-off and if it's successful
1. Change the Build Pipeline status badge with yours

Extra steps:
1. Create a new feature branch from master
1. Add a new failed test function within the tests\unit_test.py 
    1. E.g. assert 1==2
1. Create a new Pull Request to the master branch
1. Check how the pipeline fails with the new failed test
