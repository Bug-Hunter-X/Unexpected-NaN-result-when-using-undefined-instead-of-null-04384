# Unexpected NaN Result with undefined in JavaScript Function

This repository demonstrates a common JavaScript error where a function designed to handle null values unexpectedly returns NaN when given undefined arguments.

## Problem

The JavaScript function `foo` is intended to add two numbers together. If either number is null, it should return 0. However, it fails to correctly handle undefined values, leading to an NaN result.

## Solution

The solution involves explicitly checking for both null and undefined using the loose equality operator (==) or a combination of strict equality (===) and typeof checks for a more robust solution.

## Usage

The `bug.js` file contains the problematic code.  The `bugSolution.js` file demonstrates the corrected version.