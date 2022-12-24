---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

At AuthorAI we are reimagining the authoring experience powered by AI. We are exploring how state of the art in AI can enhance the creative authoring flow as it applies to creating apps, books, blogs, sites, data, designs, reports, etc.

To get started install the AuthorAI package for your Python project or Jupyter Notebook.

```
pip install authorai
```

### AuthorAI Blogger 
We created AuthorAI Blogger for human and AI in partnership for low-code blog authoring automation. We are sharing a [notebook tutorial](https://github.com/authorai/authorai/blob/main/blogger_tutorial.ipynb) so that you can join the exploration. The tutorial walks through basics of AuthorAI + human authoring flow which you can adapt to your needs. Another objective of this notebook is to act as an interactive playground for the AuthorAI library.

Here is an example of a 100% auto generated blog post by just providing three keywords as input to AuthorAI API.

You can auto generate this blog post in a single API call like so.

```python
from authorai import blogger
keywords = ['Physics', 'Art', 'City']
blogger.auto_generate(keywords, verbose=True)
```

![Generated Blogger Post](/assets/img/blogger-post.png)

### AuthorAI Blogger for Jekyll 
Jekyll is one of the most popular static website generators used among GitHub community. AuthorAI now integrates with Jekyll to generate posts straight into your Jekyll managed static website. See [notebook](https://github.com/authorai/authorai/blob/main/blogger-jekyll.ipynb) used by human author to generate a Jekyll blog post including code snippets, FAQ, multiple sections, and feature image.
