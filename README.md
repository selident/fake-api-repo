# fake-api-repo

This is a fake test suite which is used for testing the basic API test framework https://github.com/selident/basic-api-test

Any push action to this repository, or any pull request will cause a Github check to run.
That check will clone code from the repo `https://github.com/selident/basic-api-test`
Then execute API tests from that test framework. If all passed, we can feel free to merge code.
