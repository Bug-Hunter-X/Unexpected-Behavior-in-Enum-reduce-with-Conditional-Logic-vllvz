# Elixir Enum.reduce Conditional Logic Bug

This repository demonstrates a subtle bug that can occur when using Elixir's `Enum.reduce` with conditional logic within the reducer function.  The example shows how an improperly handled condition in the `if` statement can produce unexpected results.  The solution provides a corrected version with improved error handling and clarity.

## Bug Description

The original code uses `Enum.reduce` to sum numbers in a list that are greater than 3. However, if the condition is not handled completely, `Enum.reduce` might not behave as intended and might produce unintended results.

## Solution

The solution provides a revised `Enum.reduce` implementation that explicitly handles all possible conditions, preventing unexpected results and making the code more robust.