# Business days

The MSU and KBTU sections of this course share one grading tool. Write a Python
function that computes an assignment's due date: given the date the assignment
is posted and a number of business days, it returns the due date. Business days
are weekdays that are not holidays.

For example, an assignment posted on a Monday and due in 3 business days is due
on Thursday.

## Implementation

- Python 3.
- Name the function `due_date` and put it in `due_date.py`.

## Assignment

> "The model's job is to produce something plausible. Your job is to make sure
> only one thing is plausible." -- Claude

Tighten this specification to produce one plausible result. Then, for each
decision your spec makes, describe at least one input and its expected output,
usually as a table in your spec. A useful example gets a different output under
some other plausible reading of the original spec. For example:

| Input                                      | Expected output      |
| ------------------------------------------ | -------------------- |
| Posted Monday, 2026-10-19; 3 business days | Thursday, 2026-10-22 |

Repeatedly review your spec with an LLM until you have resolved the errors and
underspecified behavior it finds.

Finally, give your spec to an LLM and check that its code produces each
expected output.
