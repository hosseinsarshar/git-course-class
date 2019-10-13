[![Build status](https://dev.azure.com/azurefreecredit/inclass-failed-pipeline/_apis/build/status/inclass-failed-pipeline-test)](https://dev.azure.com/azurefreecredit/inclass-failed-pipeline/_build/latest?definitionId=8)

# git-course-class

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

