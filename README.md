# Elixir Enum.reduce Conditional Logic Bug

This repository demonstrates a subtle bug that can arise when using `Enum.reduce` in Elixir with conditional logic within the reducer function. The issue lies in how the accumulator is updated when the condition isn't met.  The provided example shows how to correctly handle such situations and avoid unexpected results.

**Bug:** The original code doesn't correctly handle cases where the condition (`x > 3`) is false, potentially leading to incorrect summation.

**Solution:** The corrected code uses a more robust approach ensuring that all cases are handled properly.