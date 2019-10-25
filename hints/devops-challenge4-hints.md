# Automatically create a work item when the build fails
## Hints
- This setting is associated with your Azure DevOps project
- More specifically, its an option on the build pipeline
- Once you have set the option, you'll have to break the build.  There are lots of ways of doing this, but I just change an equal to a notequal in one of the unit tests
- kick off your build manually if you need to
- in the DevOps portal navigate to work items to see your new bug
- undo the change you made to break the build.
- when checking in your change select the bug for the broken build from the drop down list
- Follow your build progress and on the summary page you should see the related work item.

Detailed instructions for this challenge are available [here](https://github.com/nikkh/maug3010/wiki/Simulate-a-break-in-the-build)

[back](../azure-devops-projects-mini-hack.md)

