# Between the Lines

**Explainable credibility & bias analysis for news articles.**

> Work in progress: this repository is the starting point of my term project.

## Why this project?

Misleading articles rarely appear “false” at first glance. They tend to rely on
emotional language, overbroad generalizations, a lack of sources, and
sensational headlines. Most existing tools simply provide a verdict (“false ” / “true”), which
is hard to trust and doesn’t help readers learn anything.

I wanted to create something different: a tool that **explains its reasoning**.
Based on a given article, it should help readers understand what makes the text
suspicious and allow them to form their own opinions.

## The idea

*Between the Lines* aims to:

- **Highlight** emotionally charged or biased wording directly in the text
- **Explain** how the credibility score is computed, with a clear breakdown
  of each signal instead of a single opaque number
- **Show the reliability** of the sources cited in the article
- **Cross-check claims** against existing fact-checking databases

## Status

Early stage: project setup and design. Usage instructions, screenshots and
a demo will be added as the project progresses.

## Tech (planned)

Python, with NLP libraries for text analysis and a web interface to display
the results.

## License

To be defined (planned: MIT). See `LICENSE`.

## Credits & references

Third-party libraries, datasets and APIs used in this project will be listed
here.
