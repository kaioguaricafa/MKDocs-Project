# MKDocs-Project
Projeto Kaio Guari

pip install mkdocs

mkdocs new my-project
cd my-project

$ mkdocs serve
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 0.22 seconds
INFO    -  [15:50:43] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO    -  [15:50:43] Serving on http://127.0.0.1:8000/

site_name: MkLorum
site_url: https://example.com/

curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md

site_name: MkLorum
site_url: https://example.com/
nav:
  - Home: index.md
  - About: about.md

site_name: MkLorum
site_url: https://example.com/
nav:
  - Home: index.md
  - About: about.md
theme: readthedocs

mkdocs build

$ ls site
about  fonts  index.html  license  search.html
css    img    js          mkdocs   sitemap.xml

echo "site/" >> .gitignore

