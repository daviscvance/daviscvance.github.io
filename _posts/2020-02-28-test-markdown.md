---
layout: post
title: Markdown Template
subtitle: Useful to copy ideas from
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
# share-img: /assets/img/path.jpg
tags: [markdown, test]
comments: true
last-updated: 2021-03-06
---

Big shoutout to [Dean Attali (daattali)](https://github.com/daattali) for making
this all this possible with
[beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)].

# Single Hash Heading {#custom-id}
This is a collection of markdown for quick referencing. [^1] Markdown is useful.
It helps write `HTML code` with _simplicity_. [^footnote-42]

Unfortunately, some of these features may not work outside of GitLab.
You can use GitLab Flavored Markdown in the following areas:

- Comments
- Issues
- Merge requests
- Milestones
- Snippets (the snippet must be named with a .md extension)
- Wiki pages
- Markdown documents inside repositories
- Epics (ULTIMATE)

- [x] Completed task
- [ ] Incomplete task
  - [ ] Sub-task 1
  - [x] Sub-task 2
  - [ ] Sub-task 3

1. [x] Just going to have to make do with what you can.
1. [ ] But know that there is a great beyond.
   1. [ ] For which, you can explore.
   1. [x] Uses markdown: kramdown in YAML


[^1]: Footnote 1 is just mentioning that I started with
[md guide's cheat sheet](https://www.markdownguide.org/cheat-sheet/).

[^footnote-42]: Tehe.

---

**Embolden yourself with two asterisks and also knowledge!**

## Second heading with 2 hashes

Here's a ~~striking~~ly good table:

| Number | Color? | Other |
| :--- | :------: | ---: |
| Five | `#FF0000AA` | Hey |
| 100 | `RGB(0,255,0)` | Ho |
| Seven | `RGB(0%,100%,0%)` | Watch it |
| 999 | `RGBA(0,255,0,0.3)` | Flow |

How do you like them apples? <br>
Apples
:  Tasty snack

---

![Do do do dodo](https://i.imgur.com/WsUV4DK.gif)

It can also be centered!

![Dun Da dun dun Da](https://i.imgur.com/WsUV4DK.gif){: .mx-auto.d-block :}

And here is the same code with syntax highlighting:

```javascript
var foo = function(bar) {
  return(bar + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Boxes
> Add all sorts of stuff.
> [Reference](https://en.wikipedia.org/wiki/Markdown)
> Boxes, notifications, warnings and errors galore.

### Notification

{: .box-note}
**Note:**  
 - {+ Do add color +}
 - [- but be afraid -]
 - [+ of errors +]
 - {- :tongue: -}

### Warning

{: .box-warning}
**Warning:** Hurry up or you will be late! :snail:

### Error

{: .box-error}
**Error:**
Don't use these:
[Emoji List](https://www.webfx.com/tools/emoji-cheat-sheet/) :speak_no_evil:

## DAG
```mermaid
graph TB

  SubGraph1 --> SubGraph1Flow
  subgraph "SubGraph 1 Flow"
  SubGraph1Flow(4B. If you're)
  SubGraph1Flow -- Not --> Greedy
  SubGraph1Flow -- You Will --> Go Far
  end

  subgraph "Main Graph"
  Node1[1. Oompa] --> Node2[2. Loompa]
  Node2 --> SubGraph1[3. Doompety (Jump to SubGraph1]
  SubGraph1 --> FinalThing[4A. Da]
end
```
