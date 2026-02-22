---
layout: post
title: "Working with Code Blocks in Jekyll"
date: 2026-02-22
categories: [guides, jekyll]
---
When writing technical posts, fenced code blocks are the easiest way to share commands and examples.

Here is a shell command block:

```bash
bundle exec jekyll serve --livereload
```

Here is a YAML example:

```yaml
title: Matt Hunckler
description: Personal site and blog about IT infrastructure engineering.
url: "https://matthunckler.github.io"
```

Here is a Python snippet:

```python
def check_service(name: str, status: int) -> str:
    state = "healthy" if status == 200 else "degraded"
    return f"{name}: {state}"

print(check_service("api-gateway", 200))
```

And inline code looks like this: `bundle install`.

Use language labels (`bash`, `yaml`, `python`, etc.) for syntax highlighting.
