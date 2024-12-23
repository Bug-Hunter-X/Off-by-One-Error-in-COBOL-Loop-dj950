# Off-by-One Error in COBOL Loop

This repository demonstrates a common off-by-one error in a simple COBOL loop. The program intends to count from 1 to 10, but due to the loop initialization and the condition check, it might produce an unexpected result.  The solution shows how to correct the error. 

## Bug
The `bug.cob` file contains the erroneous COBOL code. The main issue is that the loop starts at 1 and continues until `I > 10`, causing a discrepancy.

## Solution
The `bugSolution.cob` file provides the corrected code. The solution addresses the off-by-one error and fixes the loop condition for accurate counting from 1 to 10.