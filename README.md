# How to contribute

*Simple contribution guidelines to make open-source happy and organized*

Resist being a [lazy developer](http://1.bp.blogspot.com/-YD8Na5Mv4oY/USZJ0T5RKQI/AAAAAAAADnU/5U871_OaqRE/s1600/Ain-t-Nobody-Got-Time-Fo-Dat-sweet-brown-31241125-480-330.jpg), we can get through this together.

## Project organization

* Branch `master` is always stable and release-ready
* Branch `develop` is for development and merged into `master` when stable
* Feature branches should be created for adding new features and merged into `develop` when ready
* Bug fix branches should be created for fixing bugs and merged into `develop` when ready
* See also: [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model)

## Opening a new issue

1. Look through existing issues to see if your issue already exists
2. **Do not** open a duplicate issue
3. If your issue already exists, comment on its thread with any new information you have
4. For new issues, *be as descriptive as you can*
5. Provide as much information as you can on how to reproduce your issue
6. Attach screenshots, videos, GIFs if possible

## Submitting a pull request

1. Find an issue to work on, or create a new one (*avoid duplicates, please check existing issues!*)
2. Fork the repo
3. Create a new branch with a sweet fucking name: `git checkout -b issue_<##>_<featureOrFix>`
4. Do some motherfucking programming
5. Write [unit tests](http://nshipster.com/unit-testing), if possible
6. Keep your code nice and clean by adhering to coding standards & guidelines (*see below*)
7. Don't break shit, like unit tests
8. Update the documentation header comments, if needed
9. Merge the latest from the `develop` branch and **resolve any conflicts** (*before submitting a pull request!*)
10. Submit a pull request to the `develop` branch

# Style guidelines

Style and adherence to conventions is just as important as the code you write. *Don't be sloppy.* Your mother wouldn't like that.

## Objective-C style

The follow sets of guidelines compliment each other well and cover nearly everything.

* Google's [Objective-C Style Guide](http://google-styleguide.googlecode.com/svn/trunk/objcguide.xml)
* Apple's [Coding Guidelines for Cocoa](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html)
* NYTimes [Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide)

