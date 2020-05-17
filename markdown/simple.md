<!-- Ordered list -->
1. [Markdown Guide](https://www.markdownguide.org/extended-syntax/)
1. [Markdown Basics](https://daringfireball.net/projects/markdown/basics)

<!-- Headings -->
# Heading
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is italic

__This text__ is italic

<!-- Strike through -->
~~This text~~ is striker through

<!-- Horizontal Rule -->

---
___

<!-- Escape character -->
\*This text \* shows escape character

<!-- Blockquote -->
> This is a quote

<!-- Links -->
[Bhanu Kiran Chaluvadi](https://github.com/BhanuKiranChaluvadi)

[Bhanu Kiran Chaluvadi](https://github.com/BhanuKiranChaluvadi "Bhanu Kiran Chaluvadi")

<!-- Unordered List -->
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

<!-- Ordered List -->
1. Item 1
1. Item 2
1. Item 3


<!-- Inline Code Block -->
`<p> This is a paragraph </p>`

<!-- Images -->
![Markdown logo](https://markdown-here.com/img/icon256.png)

<!-- Github Markdown -->

```bash
npm install

npm start

```

```javascript
    function add(num1 ,num2) {
        return num1 + num2 ;
    }

```

```c
int main() {
    int x = SOME_MACRO_REFERENCE;
    int y = 5 + 4;
    cout << " Hello World " << x << std::endl;
}
```

```cpp
int main() {
    int x = SOME_MACRO_REFERENCE;
    int y = 5 + 4;
    cout << " Hello World " << x << std::endl;
}
```
```python
    def add(num1 ,num2):
        return num1 + num2
```

<!-- Tables -->

<!-- Tables -->
| Name                  | Email          |
| --------------------- | -------------- |
| Bhanu Kiran Chaluvadi | bkch@gmail.com |
| Bhanu Kiran Chaluvadi | bkch@gmail.com |


<!-- Task List -->

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## collapsible markdown?

<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>


<details>
<summary>How do I dropdown?</summary>
<br>
This is how you dropdown.
<br><br>
<pre>
&lt;details&gt;
&lt;summary&gt;How do I dropdown?&lt;&#47;summary&gt;
&lt;br&gt;
This is how you dropdown.
&lt;&#47;details&gt;
</pre>
</details>

---

<details open>
<summary>Want to ruin the surprise?</summary>
<br>
Well, you asked for it!
<br><br>
<pre>
&lt;details open&gt;
&lt;summary&gt;Want to ruin the surprise?&lt;&#47;summary&gt;
&lt;br&gt;
Well, you asked for it!
&lt;&#47;details&gt;
</pre>
</details>