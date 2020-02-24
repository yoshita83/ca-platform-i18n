# ca-platform-i18n
Language Internationalization for Comarch IoT Platform

# Working with the repo

1. Fork the ca-platrofm-i18n repo (if you have already done it just 'update your fork' and skip step 2: cloning repo)
2. Clone this repo locally: `git clone https://github.com/your-github-repo/ca-platform-i18n.git`
3. Create branch for task on your github: `my_owesome_branch`
4. Create branch for task on your local repo: `git checkout -b my_owesome_branch`
5. Commit your changes
6. `git remote show origin`, just to check if origin is not set
7. `git remote set-url origin https://github.com/your-github-repo/ca-platform-i18n.git`
8. `git push -u origin my_owesome_branch`, to progagate changes to your github repo
9. Make pull request to caiotplatformloc/ca-platform-i18n

# Updating your fork

1. `git remote -v`
2. If there is no upstream: `git remote add upstream https://github.com/caiotplatformloc/ca-platform-i18n.git`
3. `git fetch upstream`, to fetch changes from forked repo into upstream/master branch
4. `git merge upstream/master`, merge branch with updates to your master
5. `git push origin master`, to update you github repo
