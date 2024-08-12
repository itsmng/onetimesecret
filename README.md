# One-Time Secret 
A GLPI One-Time Secret integration

[![License](https://img.shields.io/badge/License-GNU%20AGPLv3-blue.svg)](https://github.com/ticgal/taskdrop/blob/master/LICENSE)
[![One-Time Secret](https://img.shields.io/badge/Service-One--Time%20Secret-red)](https://onetimesecret.com)

## The problem

How are you sending your passwords or secrets? Currently, there's no easy and secure way.

[One-Time Secret](https://onetimesecret.com/) is an [open source project](https://github.com/onetimesecret/onetimesecret) with a free online service that is meant for that. Nothing more and nothing less!

Read about the project here: https://onetimesecret.com/about

## What you get 

- Set up the default service
- Integrate documents generated with 3rd party plugins

## How to configure it
- On the **One-Time Secret server**. (You need an account to use the API): [One-Time Secret](https://onetimesecret.com/) 
  1. Login > Account > API Key
  2. Copy the key 
- On your **ITSM-NG instance**
  - Setup
    1. Install and activate the plugin in your ITSM-NG
    2. Setup > General > One-Time Secret
    3. Add your server URL (defaults to public one)
    4. Add your API Key
    5. Choose a default expiration (in hours) for the secret links
 - Permissions
    1. Review your existing profiles we are adding this feature ITSM-NG wide because passwords can be sent both ways
    2. Enable or disable profile-based as you like 

## How to use it
You will have a new button on your processing view.
