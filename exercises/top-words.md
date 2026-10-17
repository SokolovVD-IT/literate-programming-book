# Top words

A news site shows a "Trending words" box beside each article. Write a Python
function that finds the 10 most common words in an article's text, along with
how many times each one appears. Articles may be in English, Russian, or
Kazakh.

## Implementation

- Python 3.
- Name the function `top_words` and put it in `top_words.py`.

## Assignment

> "The model's job is to produce something plausible. Your job is to make sure
> only one thing is plausible." -- Claude

Tighten this specification to produce one plausible result. Then, for each
decision your spec makes, describe at least one input and its expected output,
usually as a table in your spec. A useful example gets a different output under
some other plausible reading of the original spec. For example:

| Input                      | Expected output         |
| -------------------------- | ----------------------- |
| `cat dog cat bird dog cat` | cat: 3, dog: 2, bird: 1 |

Repeatedly review your spec with an LLM until you have resolved the errors and
underspecified behavior it finds.

Finally, give your spec to an LLM and check that its code produces each
expected output.
