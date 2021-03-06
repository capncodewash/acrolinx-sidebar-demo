# Acrolinx Sidebar Demo

Demo code for an integration of the Acrolinx sidebar into a web application

## Prerequisites

Please contact Acrolinx SDK support (sdk-support@acrolinx.com) for initial consulting. 
We like to schedule a kickoff meeting to answer any questions about your integration project. 
After the meeting, we provide you with test server credentials and configuration settings you need to get started.

## Configuration of the Sidebar Example

Before you can run this example you need to configure some settings in these files:
  * samples/client/config.js
    * clientSignature
    * serverAddress

## How to Start
First make sure, that you have installed nodejs (which includes npm) and grunt-cli.

Then you need to install all required node modules:

    npm install

Now you can start the development server by typing:

    grunt

(If grunt complains while the bower:install task, you might have to execute "bower install" manually.)

Now open [http://localhost:9002](http://localhost:9002) in your web-browser.

![Screen Shot of Example](/doc/screenshot.png)


## Sidebar API Documentation

You can find the Sidebar API Documentation as a TypeScript .d.ts file here:  
https://support.acrolinx.com/hc/en-us/articles/205687652-Acrolinx-Sidebar-API-Reference 

## License

Copyright 2015-2016 Acrolinx GmbH

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

For more information visit: http://www.acrolinx.com


