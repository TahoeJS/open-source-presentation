# Joining the Open Source movement

## Philosophy & Why of Open Source

## Getting Started in Open Source

Contributing to open source can be intimidating:
- Any code that you submit is open to the review and criticism of the project maintainers and the public.  
- You might be afraid that people in the project won't be nice
   - Linus Torvalds is known for commenting on one pull request to the Linux kernel, "Christ people. This is just sh*t."
- There are barriers to entry in learning what and how to do it

### Tools to Get Started
- npm
- git & github
- testing framework
- node

The tools for open source are primarily the tools used by most modern developers. However, each community will be different. Many projects will require tests to be submitted with any pull request.

### Finding a Project

First, it's probably best to contribute to a project that you already use on a regular basis. If you don't use it regularly, you may be capable of making documentation updates and simple bug fixes, but you won't have the context needed for making larger bug fixes, refactors and new features. I say this because open source projects are a community, and, as such, large changes are commonly discussed before they're implemented. If you're not part of those discussions, then you may not have the context or the roadmap for the larger changes and features.

I think there are benefits and drawbacks to choosing a small project vs. a large one.
- Small projects
   - Small projects are often maintained by a few people at most. This may mean that the maintainers are happy to accept help but it may also mean that they're too busy to provide help.
   - Since they're small, it's easier to wrap your head around the whole project.  However, this may mean that the maintainers already have a specific vision for the project.
- Large projects
   - Large projects may be maintained by a large team of people. This may mean that they have time to flag beginner issues and provide feedback, but it may also mean that they're overwhelmed by pull requests
   - It would be harder to understand the entirety of a large project but it may be easier to find a small piece that you can work.
   - Large projects mean large amounts of documentation, and that always needs work

### Making a First Commit
Steps:
1. fork the repo
   1. make a new branch, if you want to keep your changes out of the master version of your fork
1. make your changes
1. create any necessary tests for new code and make sure existing tests pass
1. commit your code to your branch
   1. if you only make one commit to your branch, it should give a brief summary of the changes that you made
   1. if you make multiple commits to your branch, the project may ask you to use `git rebase` to collapse those commits into one commit that explains your contribution
1. from Github, create a pull request
   1. it depends on the project, but usually your PR will be against the master branch of the parent repo
   1. the project will probably ask that your PR contain a summary of your changes, tests, screenshots of any UI changes, etc
1. the project may ask you to sign a Contributor License Agreement (CLA)

### What to Expect
Once you submit your pull request, it is up to the maintainers. They may run automated tests against your code. The will almost certainly do a code review of it, and possibly multiple code reviews, if it is a big change.  If it's a larger change, your PR may be submitted to the larger community for comments.

### Growing as a Contributor
One common path to growth seems to be:
1. documentation fixes or improvements
1. minor bug fixes
1. larger bug fixes or features
1. ability to review pull requests and merge
1. project maintainer
   * job developing open source
   * burnout

Like any volunteer position, burnout is a possibility.  I think one of the keys to avoiding burnout is keeping a sane schedule for yourself.

### Resources
- [First Timers Only](http://www.firsttimersonly.com/)
   - Initiative by Scott Hanselman and Kent C. Dodds
   - Built to encourage project owners to make it easy for first time contributors
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
   - very detailed guide about why and how
- [Up For Grabs](http://up-for-grabs.net/)
   - aggregates Github tags such as `jump in`, `up for grabs`, `beginner friendly` to try to surface projects that are actively looking for help
- [First Pull Request](http://firstpr.me/)
   - see the first PR that you ever made
- [Contributing to the Mozilla code base](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction)
