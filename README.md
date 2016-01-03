# How to contribute

*Simple contribution guidelines to make open-source happy and organized*

Resist being a [lazy developer](http://1.bp.blogspot.com/-YD8Na5Mv4oY/USZJ0T5RKQI/AAAAAAAADnU/5U871_OaqRE/s1600/Ain-t-Nobody-Got-Time-Fo-Dat-sweet-brown-31241125-480-330.jpg), we can get through this together.

## Project organization

* Branch `master` is always stable and release-ready.
* Branch `develop` is for development and merged into `master` when stable.
* Feature branches should be created for adding new features and merged into `develop` when ready.
* Bug fix branches should be created for fixing bugs and merged into `develop` when ready.
* See also: [*A successful Git branching model*](http://nvie.com/posts/a-successful-git-branching-model).

## Opening a new issue

**Do not open a duplicate issue!**

1. Look through existing issues to see if your issue already exists.
2. If your issue already exists, comment on its thread with any information you have. Even if this is simply to note that you are having the same problem, it is still helpful!
3. Always *be as descriptive as you can*.
4. Provide as much information as you can on how to reproduce your issue.
5. Attach screenshots, videos, GIFs if possible.
6. **Include library version or branch experiencing the issue.**
7. **Include OS version and devices experiencing the issue.**

## Submitting a pull request

1. Find an issue to work on, or create a new one. *Avoid duplicates, please check existing issues!*
2. Fork the repo.
3. Create a new branch with a sweet fucking name: `git checkout -b issue_<##>_<featureOrFix>`.
4. Do some [motherfucking programming](http://programming-motherfucker.com).
5. Write [unit tests](http://nshipster.com/unit-testing) when applicable.
6. Keep your code nice and clean by adhering to the coding standards & guidelines below.
7. Don't break unit tests or functionality.
8. Update the documentation header comments if needed.
9. **Merge the latest from the `develop` branch and resolve any conflicts _before submitting a pull request!_**
10. Submit a pull request to the `develop` branch.

**You should submit one pull request per feature!** The smaller the PR, the better your chances are of getting merged. Enormous PRs will likely take enormous amounts of time to review, or they will be rejected.

# Style guidelines

Style and adherence to conventions is just as important as the code you write. Most of our time is spent reading code, not writing it. *Don't be sloppy.*

Above all, conform to the existing style of the code in which you are working. When in doubt, refer to the guides below.

## Objective-C style

The following sets of guidelines compliment each other well and cover nearly everything. In the event of contradictory rules, the order of the guides below denotes their precedence.

1. Apple's [Coding Guidelines for Cocoa](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html)
2. Google's [Objective-C Style Guide](http://google-styleguide.googlecode.com/svn/trunk/objcguide.xml)
3. NYTimes [Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide)

## Swift style

Clarity and readability should be prioritized, while redundancy should be avoided. Remember that [verboseness does not necessarily yield clarity](http://radex.io/swift/methods/). 

Adhere to the following sets of guidelines. In the event of contradictory rules, the order of the guides below denotes their precedence.

1. GitHub's [Swift Style Guide](https://github.com/github/swift-style-guide)
2. Ray Wenderlich's [Swift Style Guide](https://github.com/raywenderlich/swift-style-guide)
