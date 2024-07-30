Steps to repro:
1. Install repo
2. Run tests using vs code test runner (testing icon on the left menu, followed by play button) => test reports folder contains report with datetime of test run
3. Run tests again using the vs code test runner

   Actual: previous test report is over-written and test-reports folder contains 1 test report \
   Expected: new test report is created and test-reports folder contains 2 test reports
