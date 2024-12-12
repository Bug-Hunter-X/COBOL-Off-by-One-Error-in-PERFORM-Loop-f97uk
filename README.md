# COBOL Off-by-One Error in PERFORM Loop

This example demonstrates a common off-by-one error that can occur in COBOL PERFORM loops.  The issue stems from the loop termination condition not accurately reflecting the desired number of iterations. 

## Bug Description
The provided COBOL code snippet uses a `PERFORM VARYING` loop. There is an error in the way the counter is used, causing the loop to execute either one too many or one too few times.  This is a subtle bug which is easy to overlook. 

## Solution
The solution involves carefully reviewing the loop's termination condition and ensuring it aligns correctly with the desired number of iterations. 
