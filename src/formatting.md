# Testing `mdBook` Formatting

## 1. Basic Markdown Elements

### Headers

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

### Text Formatting

- *Italic* text
- **Bold** text
- ***Bold and Italic*** text
- ~~Strikethrough~~ text

### Lists

- Unordered list item 1
- Unordered list item 2
  - Nested item 1
  - Nested item 2

1. Ordered list item 1
2. Ordered list item 2

### Links

[mdBook Documentation](https://rust-lang.github.io/mdBook/index.html)

### Images

![Rust Logo](https://www.rust-lang.org/logos/rust-logo-512x512.png)

## 2. Code Blocks and Syntax Highlighting

### Inline Code

This is an example of `inline code`.

### Code Blocks

```rust
fn main() {
    println!("Hello, mdBook!");
}
```

### Shell Commands

```sh
echo "This is a shell command"
```

### JSON

```json
{
    "key": "value",
    "array": [1, 2, 3],
    "nested": {
        "key2": "value2"
    }
}
```

## 3. Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data 1   | Data 2   |
| Row 2    | Data 3   | Data 4   |

## 4. Admonitions with `mdbook-admonish`

### Info

```admonish info
This is an informational note.
```

### Warning

```admonish warning
This is a warning note.
```

### Error

```admonish danger
This is a danger note.
```

### Success

```admonish success
This is a success note.
```

### Tips

```admonish tip
This is a tip!
```

### Custom Titles

```admonish note title="Custom Note Title"
This is a note with a custom title.
```

## 5. Blockquotes

> This is a blockquote.
>
> It can span multiple lines.

## 6. Math

### Inline Math

Euler's identity: $e^{i\pi} + 1 = 0$

### Display Math

$$
\int_0^\infty e^{-x^2} \, dx = \frac{\sqrt{\pi}}{2}
$$

## 7. Diagrams

### Mermaid Diagrams

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## 8. Footnotes

Here's a sentence with a footnote.[^1]

[^1]: This is the footnote content.

## 9. Task Lists

- [x] Task 1 completed
- [ ] Task 2 not completed

## 10. Collapsible Sections (if supported)

<details>
  <summary>Click to expand!</summary>
  
  Hidden content here.
</details>
