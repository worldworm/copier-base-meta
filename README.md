<h1 align="center">📋 copier-base-meta</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> meta template for all projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->




## Features
- custom precreated readme
- MIT license support


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage
> **Note**
> This is a meta template that cannot be used directly to create a project.
> The template resulting from this meta-template can be used for this purpose: [copier-base](https://github.com/worldworm/copier-base)

Make sure the requirements are met, then:
```bash
copier copy "https://github.com/worldworm/copier-base-meta.git" /new/project/path
```

### Update
To update a template after creating a project, run:
```bash
copier update -a .project/.copier-answers.base-meta.yml /some/project/path
```

## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023</i><br>
  <i>Licensed under <a href="https://github.com/worldworm/copier-base-meta/blob/main/LICENSE">MIT</a></i><br>
</p>
