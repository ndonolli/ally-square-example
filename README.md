# Ally square payment form example

This is a fork of the most recent Square payment form example repository.  The issue we are trying
to demonstrate is that a simple Square "card" element does not call the inputEventReceived callback
during user input.  We believe that this was the expected behavior as of 10/7/2019.  Following that date,
we have seen a change in this behavior despite no changes in our codebases.

In this project, we have replaced the individual Square elements with the simple "card" element, and
added the inputEventReceived callback which logs the event to the console.  We are using our sandbox
application ID.

# sqpaymentform-nodejs-starterkit

* Ensure you have npm installed (`npm -v` in your terminal). If not please follow the instructions for your OS: https://www.npmjs.com/get-npm

* Open your terminal and type the following to install the packages:
```
npm install
```

* Then to run the server in production mode:
```
npm start
```

## License

```
Copyright 2019 Square Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```