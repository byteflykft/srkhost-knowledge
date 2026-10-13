# Vipy markdown syntax

## Headings

# h1
## h2
### h3
#### h4
##### h5
###### h6

```md
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

## Alerts

:::danger This is a red danger message.:::
:::warning This is a red warning message.:::
:::info This is a red info message.:::
:::success This is a red success message.:::
:::quote This is a simple quote.:::

```md
:::danger This is a red danger message.:::
:::warning This is a red danger message.:::
:::info This is a red danger message.:::
:::success This is a red danger message.:::
:::quote This is a simple quote.:::
```

## Code blocks

We use the exact same method like the original markdown blocks.

```bash
echo 'Launch Minecraft!'
```

```js
const headerMatch = trimmed.match(/^(#{1,6})\s*(.*)$/);
const orderedMatch = trimmed.match(/^(\d+)\.\s+(.*)/);
```

## Text decoration

**bold**
_italic_
`inline code`

```md
**bold**
_italic_
`inline code`
```

## Links

[Click here to open](https://google.com/)

```md
[Click here to open](https://google.com/)
```

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Ordered and unordered simple and multi-level lists

- First line
- Second line
- Third line

- First line
    - First line first-level children
        - First line second-level children
        - First line second-level children
    - First line first-level children
- Second line

1. First line
2. Second line
3. Third line

```md
- First line
- Second line
- Third line

- First line
  - First line first-level children
    - First line second-level children
    - First line second-level children
  - First line first-level children
- Second line

1. First line
2. Second line
3. Third line
```

## Tables

| Column 1 | Column 2  | Column 3 | Column 4 | Column 5 |
|----------| :-------: | :------- | -------: |----------|
| C1-R1    | C1-R1     | C3-R1    | C4-R1    | C5-R1    |
| C1-R2    | **C1-R2** | *C3-R2*  | C4-R2    | C5-R2    |
| C1-R3    | C1-R3     | C3-R3    | C4-R3    | C5-R3    |

```md
| Column 1 | Column 2  | Column 3 | Column 4 |
|----------| :-------: | :------- | -------: |
| C1-R1    | C1-R1     | C3-R1    | C4-R1    |
| C1-R2    | **C1-R2** | *C3-R2*  | C4-R2    |
| C1-R3    | C1-R3     | C3-R3    | C4-R3    |
```

## Image

![Image alt here](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif)

```md
![Image alt here](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif)
```
