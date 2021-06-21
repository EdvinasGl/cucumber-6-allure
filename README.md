# README






##### 1. Run Tests:
1. Run only tests
```shell script
npm start
```
2. Run tests with allure formatter (will generate allure-results, formatter is in support/report.js)
```shell script
npm test
```
3. Generate allure report (will generate allure-report)
```shell script
allure generate allure-results --clean -o allure-report
```
4. Open allure service with the report
```shell script
allure open
```
