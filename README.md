AeroGear Xcode Project Template
====================================

![Xcode Project Template Screenshot 1](https://raw.github.com/aerogear/aerogear-ios-xcode-template/screenshots/wizard.png)

|                 | Project Info  |
| --------------- | ------------- |
| License:        | Apache License, Version 2.0  |
| Build:          | Cocoapods  |
| Documentation:  | https://aerogear.org/docs/guides/GetStartedwithAeroGearandXcodeTemplate/ |
| Issue tracker:  | https://issues.jboss.org/browse/AGIOS  |
| Mailing lists:  | [aerogear-users](http://aerogear-users.1116366.n5.nabble.com/) ([subscribe](https://lists.jboss.org/mailman/listinfo/aerogear-users))  |
|                 | [aerogear-dev](http://aerogear-dev.1069024.n5.nabble.com/) ([subscribe](https://lists.jboss.org/mailman/listinfo/aerogear-dev))  |


## Supported versions

* if you run Xcode5.X use 1.6.1 tag
* if you run Xcode6.X use 1.6.2 tag or master

## How to install

To install the template in your current Xcode installation, please follow these steps:

1. [Download](https://github.com/aerogear/aerogear-ios-xcode-template/zipball/master) or clone the repository.
2. Move the `AeroGear` folder in the repository into the `~/Library/Developer/Xcode/Templates/Application/Project Templates` directory.  If it is the first time you install a template, the directories would be missing. A simple `mkdir -p  ~/Library/Developer/Xcode/Templates/Application/Project\ Templates/` in the command line would create the missing path.
3. Open Xcode and in the new project wizard you should see "AeroGear" under the 'IOS' section.

## Important Notice
 >The generated project uses [CocoaPods](http://cocoapods.org) for managing the library dependencies. Prior to start using the project, you should close the project window first and run `pod install` on the project's directory to initialize it. From then on, you should use the generated Xcode Workspace (.xcworkspace) to open your project.
 
 ## Documentation

For more details about the current release, please consult [our documentation](https://aerogear.org/docs/guides/GetStartedwithAeroGearandXcodeTemplate/).

## Development

If you would like to help develop AeroGear you can join our [developer's mailing list](https://lists.jboss.org/mailman/listinfo/aerogear-dev), join #aerogear on Freenode, or shout at us on Twitter @aerogears.

Also takes some time and skim the [contributor guide](http://aerogear.org/docs/guides/Contributing/)

## Questions?

Join our [user mailing list](https://lists.jboss.org/mailman/listinfo/aerogear-users) for any questions or help! We really hope you enjoy app development with AeroGear!

## Found a bug?

If you found a bug please create a ticket for us on [Jira](https://issues.jboss.org/browse/AGIOS) with some steps to reproduce it.