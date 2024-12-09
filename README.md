# Expo CLI Android Build Failure: Android Gradle Plugin Version Conflict

This repository demonstrates a common bug encountered when building Android APKs using the Expo CLI. The issue stems from conflicts in the Android Gradle Plugin versions used within the project.  This can lead to vague error messages during the build process, making it difficult to pinpoint the root cause.

## Problem
The `android/build.gradle` or `android/app/build.gradle` files may contain conflicting plugin versions, causing the build to fail. This often results in unhelpful error messages.

## Solution
The solution involves carefully reviewing and harmonizing the Android Gradle Plugin versions across all relevant Gradle files.  Ensuring consistency is key to resolving this type of build failure.  Refer to the `expoBugSolution.js` for a possible resolution.