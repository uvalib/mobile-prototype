# UVA Library Mobile App Prototype

_[Prototype Site](https://uvalib-mobile.firebaseapp.com/)_

### Setup

##### Prerequisites

Install [polymer-cli](https://github.com/Polymer/polymer-cli):
(Need at least npm v0.3.0)

    npm install -g polymer-cli


##### Setup

    git clone https://github.com/uvalib/mobile-prototype.git
    cd mobile-prototype
    bower install

### Start the development server

    polymer serve

### Run web-component-tester tests

    polymer test

### Build

    polymer build

### Test the build

This command serves the minified version of the app in an unbundled state, as it would be served by a push-compatible server:

    polymer serve build/unbundled

This command serves the minified version of the app generated using fragment bundling:

    polymer serve build/bundled

### Deploy to Firebase

    firebase deploy
