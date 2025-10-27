# Import Essentials

Import Essentials is a list of libraries and tools for Python software development that [I](https://www.doismellburning.co.uk/) consider "essential".

There's a high degree of subjectivity to that definition, but broadly speaking, it's:

> "Is this something I generally find myself reaching for in Python projects I work on"

So for example I include [Hypothesis](https://hypothesis.works/) because I regularly find myself wanting [property-based testing](https://increment.com/testing/in-praise-of-property-based-testing/),
but not [`pdb`](https://docs.python.org/3/library/pdb.html) because although it's a good tool, I rarely want a debugger and would much rather debug by improving my logging and testing and observability.

Got something you think should be on the list? [Pull Requests](https://github.com/doismellburning/import-essentials/pulls) welcomed!
I can't guarantee I'll add it, but I'm certainly up for trying things!

## The List

### [structlog](https://www.structlog.org/en/stable/index.html)

[Structured logging is great](https://www.structlog.org/en/stable/why.html) and structlog is a great tool for doing it in Python.

### [Hypothesis](https://hypothesis.works/)

[Test properties, not just specific examples](https://increment.com/testing/in-praise-of-property-based-testing/).

### [uv](https://docs.astral.sh/uv/)

"An extremely fast Python package and project manager" - I now no longer have to fiddle around manually managing virtualenvs,
it manages a lockfile, and [it's fast](https://github.com/astral-sh/uv/blob/main/BENCHMARKS.md).

### [ruff](https://docs.astral.sh/ruff/)

I want to let computers handle the mundane tasks so I can focus on the more interesting bits - ruff handles all my linting and formatting needs.

### [coverage](https://coverage.readthedocs.io/)

The more of the code that is tested, the more confidence I can have in it,
and coverage helps me see what's missed, and ensure things stay above a threshold.

### [Click](https://click.palletsprojects.com/en/stable/)

I don't write a lot of CLI tools, but when I do, Click is invaluable for handling a lot of the core CLI bits,
so I can spend my time and energy on the actual functionality.

---

[Kristian Glass](https://www.doismellburning.co.uk/)
