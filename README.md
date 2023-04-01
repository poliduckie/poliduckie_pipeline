# poliduckie_pipeline :duck:

This repository contains all the notebooks and data needed in order to run a simulation of the full control algorithm with Google Colab. It also contains code for dataset generation and NN training. 
The idea is to have a single place for all the production code that allows for testing and module integration in an easier way.

### Workflow rules
1. Anything in the master branch is deployable
2. To work on something new, create a branch off frommaster and given a descriptively name(ie: new-oauth2-scopes)
3. Commit to that branch locally and regularly push your work to the same named branch on the server
4. When you need feedback or help, or you think the branch is ready for merging, open a pull request
5. After someone else has reviewed and signed off on the feature, you can merge it into master
6. Once it is merged and pushed to master, you can and should deploy immediately

:warning: Only tested, working code should be present in the master branch. If you discover a bug on that branch, please open an issue and report it on Slack
