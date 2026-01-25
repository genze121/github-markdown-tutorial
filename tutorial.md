## 🧑‍💻⚙️ `Github Markdown Tutorial`

## To add Headings

Headings
Just like HTML, Markdown has six levels of headings. Headings in Markdown are created by putting one to six # in front of your heading text with a space separating the # and text. Each # represents a heading level with # being the largest heading and ###### being the smallest heading. Here is an example of all six heading levels.

# heading1

## heading2

### heading3

#### heading4

##### heading5

###### heading6

## To add paragraphs

Paragraphs in Markdown are the default text layout. If you just type text it will automatically be converted to a paragraph. The only important thing to know about Markdown is that if you want to separate text into two separate paragraphs you need to add a blank line between each set of text. If you instead just want to have a new line within your paragraph you can add two spaces at the end of the line and it will be converted to a new line.

## To add italics

1. Way no 1 ==> _Italics Text_

2. Way no 2 ==> *Italics Text*

## To add bold

1. Way no 1 ==> **Bold Text**

2. Way no 2 ==> __Bold Text__

## To add strike-through

- ~~Strike Text~~

- ~~1000~~ 900

## To add a website link

``Syntax to add a link ==>
[Alt Text](https://google.com)
``

[Visit my website](https://w3schools.com)

`To add tooltip in the website link`

[Welcome](https://w3schools.com "W3Schools")

## To add images

![Alt](https://www.w3schools.com/favicon.ico)

`To add tooltip in the images`

![Alt](https://www.w3schools.com/favicon.ico "W3Schools")

## To add tables

| Name | Age | Address |
| ---- | --- | ------- |
| John | 25  | USA     |
| Anna | 30  | UK      |

## Alignment of tables

1. Left ==> :-----
2. Center ==> :-----:
3. Right ==> -------:

| Name | Age | Address |
| :--- | :-: | ------: |
| John | 25  |     USA |
| Anna | 30  |      UK |

## To add horizontal line

    1. <hr>
    2. ----

## To add blockquote

> This is a blockquote text.

> > This is another blockquote text.

## To add dot

- This is a dot 1.
- This is a dot 2.
- This is a dot 3.

## Lists in markdown

> There are two types of lists. They are:- 

## a) Ordered List

1) List One
2) List two
3) List three

## b) Unordered List

- List one
- List two
- List three

## 🕸️ Combination of Ordered & Unordered List

1) List One
2) List Two
3) List Three
    - one
    - two
    - three

## Using code in the markdown

1. JavaScript Code Snippet

```js
console.log("Hello World");
```

2. Java Code Snippet

```java

class HelloWorld{
    public static void main(String[] args){
        System.out.println("Hello World");
    }
}

```

3. Python Code Snippet

```python

print("Hello World");

```

4. SQL Query Snippet

```sql

select * from user_table where username = "Hello World";

```

5. HTML Code Snippet

```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="description" content="This is a HTML Code snippet" />
    <title>Hello World</title>
  </head>

  <body>
    <h1>Hello World</h1>
    <p>This is a HTML document.</p>
  </body>
</html>
```

6. CSS Code Snippet

```css
h1 {
  background-color: aqua;
  font-weight: 700;
  font-size: 20px;
  color: red;
  line-height: 1rem;
  padding: 1rem 1rem;
  margin: 1rem 1rem;
  border: 1px solid black;
  border-radius: 15px;
  box-shadow: 0 0 3px 3px;
}
```

7. Git Snippet

```git

git init

git add .

git commit -m "First Commit"

git push origin hello_world_branch

git status

git logs

```

8. JSON Snippet

```json
{
  "name": "John Doe",
  "age": 30,
  "city": "New York",
  "isManager": false,
  "isEmployee": true,
  "hobbies": ["cricket", "chess", "football"],
  "address": {
    "street": "123 Main St",
    "state": "karnataka",
    "pinCode": 12345
  }
}
```

9. React Snippet

```js
const [counter, setCounter] = useState(0);

return (
  <>
    <p>Welcome To React: {counter}</p>
    <Button onClick={() => setCounter(counter + 1)}>Click Me</Button>
  </>
);
```

## To add highlighter in markdown

1. Way No 1 ==> <mark> Highlighted Text </mark>

2. Way No 2 ==> ==Highlighted Text==

## To add subscript and superscript

- `Subscript`

  1. Way No 1 ==> H<sub>2</sub>O

  2. Way No 2 ==> H~2~0

- `Superscript`

  1. Way No 1 ==> 2<sup>2</sup> = 4

  2. Way No 2 ==> 2^2 = 4

## To add emoji

1. Way No 1 ==> ⚙️🧑‍💻🕸️

2. Way No 2 ==> :joy: :smile:

## Inline code

This is a `for` loop example

```js
// for loop example using js code.

for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```

## Expand - Collapse

<details>
  <summary> Programming Languages </summary>

- Java
- JavaScript
- Python
- C#
- Go
</details>

## Checkbox Type Standard

- [x] Checked
- [ ] Unchecked

## Alerts in markdown

> [!Note]
> Highlights information that users should take into account, even when skimming.

> [!Tip]
> Optional information to help a user be more successful.

> [!Important]
> Crucial information necessary for users to succeed.

> [!Caution]
> Negative potential consequences of an action.

> [!Warning]
> Critical content demanding immediate user attention due to potential risks.


## Diff Code Blocks

```diff
- var userName = 'GitHub';

+ const userName = 'Git';

```


```diff

@@ Authentication @@

- Password stored in plain text

+ Password hashed using bcrypt

```

## <mark style="color:red">Next Line</mark>

This is a  
markdown example.


> [!Important]
> “Markdown itself is minimal, but platforms like GitHub add powerful semantics such as alerts, collapsible sections, and task lists.”

## Badges

![Github Repo]( https://img.shields.io/badge/github-repo-blue?logo=github)

![Javascript](https://img.shields.io/badge/logo-javascript-blue?logo=javascript)

## Representing codebase using `code` in markdown

```code

## HTML

<h1>HTML Heading One.</h1>

## JavaScript

console.log("Hello JavScript");

## Python

print("Hello Python");

## CSS

h1{
  font-weight: 700;
  font-size: 20px;
  color: beige;
  border: 1px solid #000;
  padding: 1rem;
  border-radius: 10px;
  box-shadow: 0 10px 10px rgba(0,0,0,0.1);
  text-transform: uppercase;
}

## SQL

select * from world where name = "Hello World";

## Java

class HelloWorld{
  public static void main(String[] args){
    System.out.println("Hello World");
  }
}

```

## Footnote

This is a footnote[^1].

[^1]: Footnote content.

## Definition Lists

Term 1

: Definition 1

Term 2

: Definition 2a  
: Definition 2b

## 🧑‍💻 Usage of Mathematical Formulas

1) $E = MC^2$

2) $F = M*A$

3) Area of a circle = $\pi r^2$

4) $x^2$

5) $x^4$

6) $x^{10}$

7) $D = b ^ 2 - 4*a*c$

8) $x_1$ + $y_1$ = $1$

9) $a_{i,j}^{(k)}$

10) $({a+b})^2$ = $a^2$ + $b^2$ + $2*a*b$

## Table Based Example (New)

| Name     | Email         | Password | Status        |
|----------|---------------|----------|---------------|
|Sam Altman| sam@gmail.com | sam123   | ✅ Completed  |
|Elon Musk | musk@gmail.com| musk123@ | ⌛ WIP        |
|Python    | python@gmail.com | py@123 | ❌ Not Completed |
|Javascript|js@gmail.com   | js@123    | ✅ Completed |