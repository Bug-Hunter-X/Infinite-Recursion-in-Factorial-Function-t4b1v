This repository contains a Python example demonstrating a common coding error: infinite recursion in a recursive function. The `factorial` function correctly calculates factorials for non-negative integers. However, it lacks a condition to handle negative input, resulting in an infinite recursion and a `RecursionError`. The solution demonstrates how to add a check for negative input to prevent this error.