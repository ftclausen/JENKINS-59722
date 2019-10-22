## What is this?

Illustrates issue for [JENKINS-59722](https://issues.jenkins-ci.org/browse/JENKINS-59722).

## How to reproduce?

Comment out [lines 59,60](https://github.com/ftclausen/JENKINS-59722/blob/master/build.gradle#L59,L60) in `build.gradle` to trigger usage of bundled plugins as dependencies causing
plugins not to start due to bundled plugins being too old.
