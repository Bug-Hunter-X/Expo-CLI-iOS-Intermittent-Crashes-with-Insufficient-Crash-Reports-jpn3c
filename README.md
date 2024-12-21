# Expo CLI iOS Intermittent Crashes

This repository demonstrates a bug encountered while developing a React Native application using Expo CLI. The application experiences random crashes on iOS devices, with crash reports offering minimal debugging information.  Standard troubleshooting techniques, such as cache clearing and dependency reinstallation, have proven ineffective.

## Bug Description

The application crashes intermittently on iOS devices.  Crash logs are insufficient to identify the root cause. The crashes appear random and are not tied to specific user actions or code modifications.

## Solution

The solution involved a more in-depth debugging process involving the use of remote debugging, enabling detailed logging, and examining the device logs directly on the affected iOS device to pinpoint the exact area that triggered the crash and solve the problem. In this case, it might be a memory leak or a race condition that was difficult to detect by standard debugging techniques.