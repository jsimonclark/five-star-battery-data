# Five-Star Battery Data MOOC

> **Archive.** This repository preserves the original Sphinx-based MOOC. It is no longer actively developed — active development has moved to [battery-genome/five-star-battery-data](https://github.com/battery-genome/five-star-battery-data).

Welcome to the source repository for the **Five-Star Battery Data** MOOC — a self-paced course designed to help researchers, developers, and data stewards make battery data more open, structured, and machine-actionable.

## About the Course

Battery data is often underutilized due to poor accessibility, lack of structure, and missing metadata. This course teaches you how to apply modern data practices — inspired by the Semantic Web, FAIR principles, and linked data — to transform raw measurements into reusable research assets.

The course follows the **Five-Star Battery Data** framework:

1. ⭐ Publish your data on the web with a permissive license
2. ⭐⭐ Use structured data (e.g., tables, JSON)
3. ⭐⭐⭐ Use open formats (e.g., `.csv`, `.json`, `.parquet`)
4. ⭐⭐⭐⭐ Describe your data with ontologies
5. ⭐⭐⭐⭐⭐ Link your data to other relevant resources

## Get Started

The course is hosted on GitHub Pages. [Click here](https://jsimonclark.github.io/five-star-battery-data/) to get started.

## Building Locally

The Sphinx source is in the `mooc/` directory of the pre-migration commits.

```bash
pip install -r mooc/sphinx-requirements.txt
cd mooc
make html
```

The built site will be written to `mooc/_build/html/`.

## Active Development

The course is now maintained as a Battery Genome learning-content package at [battery-genome/five-star-battery-data](https://github.com/battery-genome/five-star-battery-data).

## License

All content is published under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license unless otherwise stated.
