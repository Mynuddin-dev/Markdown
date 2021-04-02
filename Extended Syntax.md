# **Extended Syntax**
---
### Tables
To add a table, use three or more hyphens (---) to create each column’s header, anduse pipes (|) to separate each column. You can optionally add pipes on either end of the table.

| Column1     | Column2        | Column3          |
| :---------- | :------------: |----------------: |
| Header      | Title          | This is 1st row  |
| Paragraph   | Text           | This is 2nd row  |
| Info        | Info           | Info             |
| Info        | Info           | Info             |

**Alignment**
You can align text in the columns to the left, right, or center by adding a colon (:) to the  ***left, right, or on both side*** of the hyphens within the header row.

[Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables "Speedy way to create table").


## **Fenced Code Blocks**
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

~~~java
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
~~~

```Python
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.
    Indent paragraphs to include them in the footnote.
    `{ my code }` 
    Add as many paragraphs as you like.


### **Definition Lists**
---
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

**Strikethrough :** ~~The world is flat.~~ We now know that the world is round.1 The world is ~~flat~~ round.

### Task Lists
---
Task lists allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
- [ ] He he he he he

#### Automatic URL Linking
Link as a link : https://github.com
Link as a text : `https://github.com`


