# Incorrect Null Check in JavaScript Function

This repository demonstrates a common error in JavaScript: incorrect null checks. The `foo` function uses loose comparison (`==`) to check for null values, which can lead to unexpected behavior.  This is because `0 == null` evaluates to `false` while `0 === null` evaluates to `false`, and `'0' == null` evaluates to `false` while `'0' === null` evaluates to `false` as well.

The solution uses strict comparison (`===`) to fix the issue. Strict comparison checks both the value and the type, preventing unexpected results.
