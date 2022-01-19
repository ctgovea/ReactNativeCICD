# Deploy to TestFlight using Fastlane and CircleCI

Repository for the post [Friendly Guide to Deploy a React Native iOS app to TestFlight using Fastlane and CircleCI](https://carlostorresg.com/friendly-guide-to-deploying-ios-testflight).


This is a sample blank React Native application created with `npx react-native init` featuring:

* Creating and reading signing secrets (certificates and provisioning profiles) with `fastlane match
* A Bitbucket match repo to store signing secrets
* Building the iOS app with `fastlane gym` action
* Deploying to TestFlight
* CircleCI pipeline to build and deploy to TestFlight
