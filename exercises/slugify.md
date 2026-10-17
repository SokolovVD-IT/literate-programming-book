# Slugify

A news site publishes articles in Kazakh, Russian, and English. Each article's
URL ends in a _slug_ made from its title. For example, an article titled "Hello,
World!" lives at `https://news.example.com/articles/hello-world`.

Write a Python function that converts an article title into a slug. Slugs must
be readable, contain only letters, digits, and hyphens, and be no longer than 60
characters.

The function must handle titles such as:

- Hello, World!
- Привет, мир!
- Ёжик в тумане
- Съешь же ещё этих мягких французских булок, да выпей чаю
- Қазақстан Республикасының Конституциясы
- Әліпби: жаңа нұсқа
- Ғылым күні
- Өскемен: жиһаз дүкені
- Алматы — Астана
- Python үшін 5 кеңес

## Implementation

- Python 3.
- Name the function `slugify` and put it in `slugify.py`.

## Assignment

> "The model's job is to produce something plausible. Your job is to make sure
> only one thing is plausible." -- Claude

Tighten this specification to produce one plausible result. Then, for each
decision your spec makes, describe at least one input and its expected output,
usually as a table in your spec. A useful example gets a different output under
some other plausible reading of the original spec. For example:

| Input           | Expected output |
| --------------- | --------------- |
| `Hello, World!` | `hello-world`   |

Repeatedly review your spec with an LLM until you have resolved the errors and
underspecified behavior it finds.

Finally, give your spec to an LLM and check that its code produces each
expected output.
