# Demo App: Auto-Increment Build Number for Native Builds in Appflow using Trapeze

This app demonstrates how Trapeze can be used to auto-increment the build number for native builds in Appflow as described in [Ionic's cookbook](https://ionic.io/docs/appflow/cookbook/auto-incrementing-build-numbers). 

## Prerequisites

To test this app, you will need to have an Appflow account with the ability to run native builds. Refer to our [pricing page](https://ionic.io/pricing) for additional details.

## Steps

1) Clone this repo
2) Run <code>ionic link</code> to associate this project to a new app within your Appflow dashboard. 
3) Commit and push changes
4) Open the Appflow dashboard to confirm that latest commit was detected
5) Run a native build
6) Open the build logs and check for the new build number under the <code>build_pro_app</code> build step during the execution of the <code>appflow:build</code> script. 

![Incremented build number in logs](/assets/images/Incremented-build-number-in-logs.png)