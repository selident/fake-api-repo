# fake-testsuite

This is a fake test suite.

Any push action to this repository, any pull request will cause a github check to run.
That check will clone code from repo `https://github.com/selident/basic-api-test`
Then execute API tests from that suite. If all passed, we can feel free to merge code.
