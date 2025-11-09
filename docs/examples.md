# Markdown Examples

This page demonstrates various Markdown features available in this MkDocs setup.

## Code Blocks

### Basic Code Block

```python
def hello_world():
    print("Hello, World!")
    return True
```

### Code Block with Line Numbers

```python linenums="1"
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
```

## Admonitions

!!! note "Note"
    This is a note admonition. Use it for important information.

!!! tip "Tip"
    This is a tip. Great for helpful hints!

!!! warning "Warning"
    This is a warning. Use for cautionary information.

!!! danger "Danger"
    This is a danger box. Use for critical warnings.

## Collapsible Sections

??? note "Click to expand"
    This content is hidden by default. Click the header to expand it.
    
    You can put any content here, including:
    
    - Lists
    - Code blocks
    - Images
    - Links

## Tabs

=== "Python"
    ```python
    print("Hello from Python!")
    ```

=== "JavaScript"
    ```javascript
    console.log("Hello from JavaScript!");
    ```

=== "Bash"
    ```bash
    echo "Hello from Bash!"
    ```

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [x] Another completed task
- [ ] Another incomplete task

## Emojis

This setup supports emojis! :rocket: :smile: :heart: :fire:

## Tables

| Feature | Status | Notes |
|---------|--------|-------|
| MkDocs | ✅ | Working |
| Material Theme | ✅ | Configured |
| GitHub Pages | ✅ | Auto-deploy |
| Search | ✅ | Enabled |

## Footnotes

Here's a sentence with a footnote[^1].

[^1]: This is the footnote content.

## Inline Code Highlighting

You can highlight inline code: `` `python:print("hi")` `` or just plain `` `code` ``.

## Links

- [MkDocs Documentation](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

## Images

![Placeholder](https://via.placeholder.com/400x200?text=Example+Image)

## Block Quotes

> This is a block quote. Use it to highlight important quotes or citations.
> 
> It can span multiple lines.

