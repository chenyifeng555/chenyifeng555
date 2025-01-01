name: Build and Test

on:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout Repository
      uses: actions/checkout@v4
      uses: actions/checkout@v3

    - name: Setup Node.js environment
      uses: actions/setup-node@v4.0.1
      with:
        node-version: 10.15.1
        node-version: 20

    - run: npm install -g bats

   
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
