# .github-workflows-runner-test.yml
name: Test Self-Hosted Runner  on:   push:     branches: [ main ]  jobs:   test-runner:     runs-on: self-hosted     steps:       - name: Say Hello from EC2         run: echo "🎉 Hello from your self-hosted EC2 runner!"
