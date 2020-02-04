## About
WebdriverIO is a test automation framework. In this repository, a web End-to-End testing will be run with ChromeDriver.

## Setup
1. Install and manage driver and Selenium server by webdriver-manager:
    ```sh
    npm install -g webdriver-manager
    webdriver-manager update
    webdriver-manager start
    ```
2. Install the Node.js modules:
    ```sh
    cd /path/of/this/repo
    npm install
    ```

## Run Test
```sh
npm test
```

## Future Work
- Dockerize this application.
- Integrate with CI system.

## Reference
- https://webdriver.io/docs/gettingstarted.html
- https://eden-liu.com/frontend/taste-webdriverio/
- https://eden-liu.com/devops/webdriverio-with-ci/