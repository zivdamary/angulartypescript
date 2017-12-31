This folder contains code samples from the book "Angular Development with TypeScript", Second Edition (see https://www.manning.com/books/angular-development-with-typescript-second-edition). It's work in progress. All code samples use Angular 5. The folder MEAP_v2 has the code samples for the December's book release. The folder MEAP_v3 is for the upcoming one (we split the chapters).

We used Angular CLI 1.6.0 for projects generation. Install it globally to run these samples.

In chapter 2, code samples are separate projects and you need to switch to the project directory you'd like to run (e.g. pipes), run npm install and then ng serve. The same applies to the sample app ngAuction that exists in most of the chapters.

In other chapters, multiple code sample apps are included in the same project, e..g. chapter3/router-samples. To run a particular app, you need to know its name - open the file .angular-cli.json and see the names of the apps configured in the apps property there. For example, the first app is configured as ```"name": "basic"```. To run this app (after you did npm install), run the following command: ```ng serve --app basic```.

You can read more about configuring multiple apps in the same project here: https://yakovfain.com/2017/04/06/angular-cli-multiple-apps-in-the-same-project

Starting from chapter 5 (MEAP_v2) or chapter 7 (MEAP_v3) we build an ngAuction app that uses Angular Material and Flex Layout libraries.

Consider watching the video Angular Applied from http://bit.ly/2iiKjDV, where Yakov Fain shows how to build apps from scratch using Angular CLI: 

For Angular training inquiries send an email to training @ faratasystems.com
