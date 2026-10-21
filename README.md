## Meshinchi and Locatelli Lab Documentation

This repository contains the internal documentation for creating, maintaining, and contributing to the Meshinchi and Locatelli Lab's software and data analysis pipelines on github. 

Find the rendered documentation linked in the repository description.

### Render the site locally

The site is a [Quarto](https://quarto.org/docs/download/) website.

```bash
gh repo clone Meshinchi-Lab/contributing_guidelines
cd contributing_guidelines

# live preview in a web browser while editing the .qmd files
quarto preview

# build the full site into docs/
quarto render
```

GitHub Pages publishes the `docs/` directory on the `main` branch, so commit the updated `docs/` files along with the `.qmd` changes.

The current site was rendered with Quarto 1.7.32 (check yours with `quarto --version`).
