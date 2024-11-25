# Introduction

## Markdown ?

#### Markdown is a lightweight markup language designed to format text in a simple and readable way. It is commonly used for creating content for websites, documentation, or technical writing due to its ease of writing and conversion to HTML.

## The comparison between and MS Word/ Google Docs

- Markdown: Plain text - Suitable for writing technical documents.
  
- MS Word & Google Docs: Visualize Editor - Suitable for general writing purposes.

## How Markdown Works
> Markdown uses simple syntax to format text, for example

### 1. Plugin

- Markdown All in One 
- Markdown Preview Enhanced

### 2. Headings : Use the # character to create headings.

- `# Heading 1` 
- `## Heading 2` 
- `### Heading 3`

### 3. Formatting:

- Bold: **Bold text** or __Bold text__-> Text
- Italic: *Italic text* or _Italic text_ -> Text
- Strikethrough: ~~Strikethrough text~~ -> Text
- Normal text: `Normal text` -> Text
- >Blockquotes: > Blockquotes -> Text

### 4. Links and images

- Link: [Link text]([link url](https://www.google.com))
- Imange : ![Image alt text]([image url](https://via.placeholder.com/150))

### 5. Table

| Cột 1  | Cột 2     | Cột 3     |
| ------ | --------- | --------- |
| Hàng 1 | Giá trị 1 | Giá trị 2 |
| Hàng 2 | Giá trị 3 | Giá trị 4 |


### 6. Code style

```php
<?php
echo;
```
```js
console.log('Hello World');
```


### 7. Graph

##### Mermaid
  
```mermaid
graph TB
    sq[Square shape] --> ci((Circle shape))

    subgraph A
        od>Odd shape]-- Two line<br/>edge comment --> ro
        di{Diamond with <br/> line break} -.-> ro(Rounded<br>square<br>shape)
        di==>ro2(Rounded square shape)
    end

    %% Notice that no text in shape are added here instead that is appended further down
    e --> od3>Really long text with linebreak<br>in an Odd shape]

    %% Comments after double percent signs
    e((Inner / circle<br>and some odd <br>special characters)) --> f(,.?!+-*ز)

    cyr[Cyrillic]-->cyr2((Circle shape Начало));

     classDef green fill:#9f6,stroke:#333,stroke-width:2px;
     classDef orange fill:#f96,stroke:#333,stroke-width:4px;
     class sq,e green
     class di orange

```
 
### 8. Fomula math

- $S(z) = \frac{1}{1 + e^{-z}}$

### 9. Import file

@import "sample_data.csv"


### 10. HTML

<div align="center">
  <img src="image.png" alt="Description" width="300">
</div

