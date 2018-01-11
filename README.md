# slides

Slides of the subject "Sistemas Multimedia"

## Clone with:
```
git clone --recurse-submodules git@github.com:Sistemas-Multimedia/slides.git
```

## Update with:
```
git submodule update --remote 
```

## Show slides with:
```
# Reveal (default)
jupyter nbconvert slides.ipynb --to slides --post serve

# Reveal with vertical scrolling
jupyter nbconvert slides.ipynb --to slides --post serve --SlidesExporter.reveal_scroll=True

# Reveal selecting theme
jupyter nbconvert slides.ipynb --to slides --post serve --SlidesExporter.reveal_theme=simple

# Reveal selecting port
jupyter nbconvert slides.ipynb --to slides --post serve --ServePostProcessor.port=8010

# Full (single page)
jupyter nbconvert slides.ipynb --to slides --template full.tpl

## full.tpl can be located at:
~/.pyenv/versions/3.6.3/lib/python3.6/site-packages/nbconvert/templates/html/full.tpl
```

