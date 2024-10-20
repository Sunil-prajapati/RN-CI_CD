

CI/CD Pipeline

1.Setup the git
    1.)create three branches as following
        Master
        staging
        feature
    2.)Git actions Invite devs
        Accept invite and create feature branch
        work on new feature then push the code
        Review/ YAML file for CI/CD
        Tested on staging(dev)
        Merged to Master(main) lock the version

2.Test Driven development
    Push the code on Git
    there will husky which will test the code 
    then merge the code into dev branch 
    if get failed then send message to slack/team
    when we got passed then merged into master
    update the app semantic version
    use jenkins pipelines/Expo CI(best in the case react-native)
    fastlane
    auto deploy on play store and app store


Github flow & Best Practices (Questions)
    Does this workflow scale with team size?
    Is it easy to undo mistakes and errors with this workflow?
    Does this workflow impose any new unnecessary cognitive overhead to the system?


3.Types of branches
    Feature Branching
    Gitflow workflow
    forking workflow(in case of open source contribution)


4.Guidelines
    Short lived branches
    minimize reverts
    match a release schedule

5. Trunk-Base Development 
	When we have only small team and we need things quickly 
	In this there will be not staging branch for testing and workflow
	Most of the startup use this development

6. Version control strategy
	Large team
		Main(hotfixes)
		Staging
		Features
	Small team 
		Main(hotfixes)
		Feature

7. Prettier and Eslint before CI/CD implementation
	We should also implement both things in our CI/CD
8. Scrum / kanban

	SCRUM:  We have match the timeline in case of scrum and if we completed the before 	time time we can rest if not then do the work by extend our working hours
   KANBAN:  We can pick the task acc. To architect of app , and all tasks has been assigned in the first go


