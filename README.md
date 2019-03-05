# app-ta-deployment

Travel agent deployment project to deploy cf apps

## Available travel-agent features

**build**

Performs a build process `YOUR_APP/ci/tasks/build.sh` prior to the push. This should only happen before pushing to the lower environment to keep consistency.

**test**

Test process `YOUR_APP/ci/tasks/test.sh` prior to the build or push. 
