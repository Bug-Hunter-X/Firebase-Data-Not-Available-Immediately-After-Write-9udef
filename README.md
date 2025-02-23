# Firebase Data Not Available Immediately After Write

This repository demonstrates a common issue when using Firebase's Realtime Database: data not being immediately available after a write operation.  The example shows how to handle this asynchronously using Promises.

## Problem

When writing data to the Firebase Realtime Database, there's a delay before the data is fully reflected in your app. Attempting to read the data immediately after writing may result in an error or null values.

## Solution

The solution involves using asynchronous operations.  The provided code demonstrates how to use `Promise` to wait until the data is available before attempting to access it.