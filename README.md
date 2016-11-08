# ci

###   travis.yml

  ```
  language: node_js
  node_js:
    - "6.4.0"
  before_script:
    -npm install
  script:
    -npm test

  ```

###   dependencies

```
"dependencies": {
  "chai": "^3.5.0",
  "chai-http": "^3.0.0",
  "dotenv": "^2.0.0",
  "mocha": "^3.1.2"
}

```
