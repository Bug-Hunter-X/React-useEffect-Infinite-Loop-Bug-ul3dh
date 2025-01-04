# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: an infinite loop caused by the `useEffect` hook.

## Problem

The `useEffect` hook in `bug.js` is designed to log the current count to the console. However, it is missing or has incorrect dependency array causing the effect to trigger on every render. This leads to an infinite loop of renders and log messages.