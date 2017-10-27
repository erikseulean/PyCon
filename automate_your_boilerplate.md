## Automate your boilerplate

- Structure your project and keep consistency between projects. Same directory structure between projects. 
- Use a template for your project and reuse it.

#### Cookiecutter 
- jinja2 templating engine
- pre/post hooks
- language agnostic

https://drivendata.github.io/cookiecutter-data-science
https://github.com/audreyr/cookiecutter

`pip install cookiecutter`\
`cookiecutter path/to/template`\
or\
`cookiecutter gh:path/to/github/repo`

**Pros**
- faster project startup time
- less distractions, more focus on issue
- consistent layouts

**Con**
- time and effort to create/debug

### What would you add next?
- docker
- ci build
- tests
- packaging
- logging

Add components as needed.

## Masonry 
- render each template layer
- a way to handle dependencies between them
- a way to store state information for the project
- setup/add template as needed

`pip install masonry`\
`mason init path/to/masonry-templates`\
`mason add template_layer`

[Slides](https://speakerdeck.com/mrkriss/automate-your-boilerplate)