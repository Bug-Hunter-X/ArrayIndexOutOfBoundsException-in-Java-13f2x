# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java programming error: accessing an array element beyond its valid index range.  The `BuggyCode.java` file contains the faulty code, which leads to an `ArrayIndexOutOfBoundsException`. The corrected code is available in `CorrectedCode.java`.

**Problem:**
The loop condition in the original code (`i <= arr.length`) causes the loop to iterate one time too many, resulting in an attempt to access arr[5] when the array only has indices 0 through 4. 

**Solution:**
The corrected code changes the loop condition to `i < arr.length`, ensuring that the loop terminates before exceeding the valid index range.