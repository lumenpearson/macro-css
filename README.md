A minimal set of out-of-the-box CSS classes for everyday layout tasks.

## Installation

NPM:
`npm install macro-css`.

Yarn:
`yarn add macro-css`.

## Usage

Install a set of classes using NPM or Yarn

### React

Plug in anywhere in index.js: `import 'macro-css';`

### SASS/SCSS

Open the main styles file and write `@import 'macro-css';` at the very beginning.

At the bottom of the table are examples of classes that can be used. Instead of the “\*” symbol, specify one letter of either side. If you don't specify a side, indents will be specified on all sides.

Side => abbreviation:

- `left` => `l`.
- `right` => `r`
- `top` => `t`
- `bottom` => `b`

### For example:

| Class | Value |
| ------------------- | ------------------------------------------------------------- |
| ``mr-10 mb-50`` | `margin-right: 10px; margin-bottom: 50px;`` |
| `m-25` | `margin: 25px;| |
| `p-50` | `padding: 50px;` |
| `pr-10 mt-15 mb-15` | `padding-right: 10px; margin-top: 15px; margin-bottom: 15px;` | |

Value:

- `mt-10` - `margin-top: 10px`.
- `mr-40` - `margin-right: 40px`

# Margin

| Class  | Value            |
| ------ | ---------------- |
| m\*-5  | margin-\*: 5px;  |
| m\*-10 | margin-\*: 10px; |
| m\*-15 | margin-\*: 15px; |
| m\*-20 | margin-\*: 20px; |
| m\*-25 | margin-\*: 25px; |
| m\*-30 | margin-\*: 30px; |
| m\*-35 | margin-\*: 35px; |
| m\*-40 | margin-\*: 40px; |
| m\*-45 | margin-\*: 45px; |
| m\*-50 | margin-\*: 50px; |

# Padding

| Class  | Value             |
| ------ | ----------------- |
| p\*-5  | padding-\*: 5px;  |
| p\*-10 | padding-\*: 10px; |
| p\*-15 | padding-\*: 15px; |
| p\*-20 | padding-\*: 20px; |
| p\*-25 | padding-\*: 25px; |
| p\*-30 | padding-\*: 30px; |
| p\*-35 | padding-\*: 35px; |
| p\*-40 | padding-\*: 40px; |
| p\*-45 | padding-\*: 45px; |
| p\*-50 | padding-\*: 50px; |

# Clearing base styles

| Class | Value                                                                                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| clear | Clears the base styles that the browser sets for: `<a>, <ul>, <li>`. Also for all (`*`) other elements: `box-sizing: border-box; outline: none` |

# Flex, позиционирование, размер

| Class           | Value                           |
| --------------- | ------------------------------- |
| h100p           | height: 100%;                   |
| w100p           | width: 100%;                    |
| d-ib            | display: inline-block;          |
| d-if            | display: inline-flex;           |
| d-flex          | display: flex;                  |
| d-block         | display: block;                 |
| justify-between | justify-content: space-between; |
| justify-around  | justify-content: space-around;  |
| justify-center  | justify-content: center;        |
| align-center    | align-items: center;            |
| align-end       | align-items: flex-end;          |
| align-start     | align-items: flex-start;        |
| flex-column     | flex-direction: column;         |
| flex-row        | flex-direction: row;            |
| flex-wrap       | flex-wrap: wrap;                |
| flex-auto       | flex: 1 1 auto;                 |
| flex            | flex: 1;                        |
| m-auto          | margin: auto;                   |
| ml-auto         | margin-left: auto;              |
| mr-auto         | margin-right: auto;             |
| text-center     | text-align: center;             |
| pos-r           | position: relative;             |
| pos-a           | position: absolute;             |

# Text

| Class           | Value                                                           |
| --------------- | --------------------------------------------------------------- |
| text-center     | text-align: center;                                             |
| text-capitalize | text-transform: capitalize;                                     |
| text-uppercase  | text-transform: uppercase;                                      |
| text-lowercase  | text-transform: lowercase;                                      |
| text-truncate   | white-space: nowrap; overflow: hidden; text-overflow: ellipsis; |
| fw-bold         | font-weight: bold;                                              |

# Opacity

| Class      | Value         |
| ---------- | ------------- |
| opacity-1  | opacity: 0.1; |
| opacity-2  | opacity: 0.2; |
| opacity-3  | opacity: 0.3; |
| opacity-4  | opacity: 0.4; |
| opacity-5  | opacity: 0.5; |
| opacity-6  | opacity: 0.6; |
| opacity-7  | opacity: 0.7; |
| opacity-8  | opacity: 0.8; |
| opacity-9  | opacity: 0.9; |
| opacity-10 | opacity: 1;   |
