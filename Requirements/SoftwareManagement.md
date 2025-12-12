# A robot software management strategy for 2026?
## Should we try this? 
- **main** - The all correct version of robot software - will be saved at the end of the target robot's usefull life.
- **develop** branch off **main** - The evolving test software for software and robot development. The develop branch will integrate all features and be tested on the robot before competition. It should always be tested code so it can be used as the base for feature development. 
- **comp** branch off **develop** - The branch to use during competition and events. A correct branch with some modifications made and tested during competion. 
- **feature** branch off **develop** : Where individual features are developed  When work on the feature is ready for integrated testing Mitchell, Sr, or Matt will review the changes and merge in to develop.
- **named** working branch off of feature : This is where you do your work. Keep all the work focused on the associated feature. When the work is complete merge it to the feature branch and delete the **working** branch. The work can be tested on the robot by building and deploying this branch.
## At the end of your work period or meeting, push your changes to the origin on Github to back up your work.
# Before you start working always make sure you are working on the right branch.
