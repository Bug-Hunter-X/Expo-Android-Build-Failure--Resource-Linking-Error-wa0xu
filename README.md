# Expo Android Build Failure: Resource Linking Error

This repository demonstrates a bug encountered when building an Android APK using the Expo CLI.  The build process fails with a generic "resource linking failed" error, making debugging difficult.  The solution involves identifying and resolving conflicts within the app's resources.

## Problem

The Expo CLI build process for Android fails, producing an error message similar to: 

`Execution failed for task ':app:processDebugResources'. > A failure occurred while executing com.android.build.gradle.internal.tasks.Workers$ActionFacade > Android resource linking failed`

This lacks specificity, hindering the troubleshooting process. 

## Solution

The solution focuses on identifying and resolving potential conflicts or errors in the app's resources, such as duplicate resource names or issues with vector drawables.  The `bugSolution.js` file provides an example of a cleaned-up resource structure that should resolve the issue. Detailed steps may vary depending on the specific cause.