# Customizing Xcode file header comments

Put the IDETemplateMacros.plist file in the correct location. It could be placed in one of five locations, depending on the range it needs to cover.

- **Project user data:**\
``<ProjectName>.xcodeproj/xcuserdata/[username].xcuserdatad/IDETemplateMacros.plist``\
  using that location would cover a specific project for just a single developer.
  
- **Project shared data:**\
  ``<ProjectName>.xcodeproj/xcshareddata/IDETemplateMacros.plist``\
  using that location would cover a specific project for the whole team using the workspace.
  
- **Workspace user data:**\
``<WorkspaceName>.xcworkspace/xcuserdata/[username].xcuserdatad/IDETemplateMacros.plist``\
using that location would cover all projects in the workspace for just a single developer.

- **Workspace shared data:**\
``<WorkspaceName>.xcworkspace/xcshareddata/IDETemplateMacros.plist``\
using that location would cover all projects in the workspace for the whole team using the workspace.

- **User Xcode data:**\
  ``~/Library/Developer/Xcode/UserData/IDETemplateMacros.plist``\
  for all projects edited by the local user.
  
That wide location choice is useful if you work on multiple projects with different header conventions or you want to share a default header comment format with other team members.

**[Reference](https://matrejek.eu/posts/customizing-xcode-header-comments/)**

# Apple Documentation

**[Text macro format reference](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/devc8a500cb9)**

**[Text macros reference](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/dev7fe737ce0)**
