# Split the bill

Write a Python function that splits a restaurant bill evenly among a group of
diners, including a tip. It takes the bill total, the tip percentage, and the
number of diners, and returns the amount each diner owes. The bill total
includes sales tax.

For example, three friends who share a $90.00 dinner and leave a 20% tip each
pay about $36.

## Implementation

- Python 3.
- Name the function `split_bill` and put it in `split_bill.py`.

## Assignment

> "The model's job is to produce something plausible. Your job is to make sure
> only one thing is plausible." -- Claude

Tighten this specification to produce one plausible result. Then, for each
decision your spec makes, describe at least one input and its expected output,
usually as a table in your spec. A useful example gets a different output under
some other plausible reading of the original spec. For example:

| Input                               | Expected output  |
| ----------------------------------- | ---------------- |
| Bill total $90.00, 0% tip, 3 diners | $30.00 per diner |

Repeatedly review your spec with an LLM until you have resolved the errors and
underspecified behavior it finds.

Finally, give your spec to an LLM and check that its code produces each
expected output.
