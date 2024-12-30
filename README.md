stages:
  - build
  - test


build-job:
  stage: build
  script:
    - echo "update maven:3.8.5-openjdk-11-slim"
    - echo "update complete."


lint test job:
  stage: test 
  script:
    - echo "test maven:3.8.5-openjdk-11-slim"
    - echo "test maven:3.8.5-openjdk-11-slim code"
