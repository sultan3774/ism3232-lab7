# debug_log.md
# Author: Sultan Alsereidi

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 13
What the error means: The dictionary does not have the key 'amount'.
What I told the duck: The function starts total at zero, loops through each record, adds its amount to total, and returns the final total.
What I tried: I added a DEBUG print to inspect the record.
How I fixed it: I changed 'amout' to 'amount' in the first record and removed the DEBUG print.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 19
What the error means: Python cannot compare an integer and a string using >.
How I fixed it: I removed the quotes around '1000' so both values are integers.

## After Fixing Both Bugs
Final output:
Total: $5150.00 across 3 records
True

Did pytest pass? Yes. All 13 tests passed.
## AI Literacy Reflection
Did I use AI? Yes.
Exact prompt I used: "what"
What AI explained: AI explained the errors and what they mean.
What I changed myself: I edited the files in VS Code and ran the script and tests.
Can I explain every fixed line? Yes

## What I Learned
I learned that dictionary keys must match exactly.
I also learned that numbers in quotes are strings, and tests help check my code.