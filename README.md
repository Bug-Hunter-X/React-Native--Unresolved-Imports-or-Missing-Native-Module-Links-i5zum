# React Native Unresolved Imports or Missing Native Module Links

This repository demonstrates a common React Native issue where native modules or components are not properly linked, resulting in runtime errors indicating unresolved imports.  The `bug.js` file showcases the error, while `bugSolution.js` provides the solution.

## Problem

Attempting to use a component or functionality from a library that hasn't been linked to your project correctly.  This usually involves native modules and will result in an error similar to "Cannot find module ..." or similar during runtime, even if the import statement seems correct.

## Solution

The solution generally involves ensuring proper linking of the native module for your platform (Android and/or iOS) as per library documentation.  This often involves running specific commands in your terminal and potentially configuring build settings in your Android (Android Studio) or iOS (Xcode) project.