# Home Page

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotations

### Codeblocks

Some `code` goes here.

### Plain codeblock

A plain code block:

```python
Some code here
def myfunction()
// some comment
```

#### With a title

```py title="bubble_sort.py"
def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) -1 -i):
                if items[j] > items[j +1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
```

#### WIth line numbers

```py linenums="1"
def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) -1 -i):
                if items[j] > items[j +1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlight lines

```py hl_lines="2 3"
def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) -1 -i):
                if items[j] > items[j +1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emojis

:smile:

:fontawesome-regular-face-laugh-wink: