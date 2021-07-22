# HTML + CSS Fundamentals

---

## 1. HTML boilerplate

### Terminology

#### What is a tag in HTML?

A tag in HTML describes the content that lives inside it to a browser. A tag name is is written
inside angled brackets `< >`. There are many different tags that exist in HTML to describe the
content of the page. For example, a `<p>` tag describes a paragraph, a `<section>` tag describes a
section, an `<li>` tag describes a list item, a `<label>` describes a form input label, and so on.

```html
<section>
  <p>
    Here's an example of a sentence inside a paragraph tag. This paragraph lives inside a section on
    the page.
  </p>
</section>
```

Most tags in HTML require an opening and closing tag to be valid, with some exceptions such as an
`<img />` and `<input />` tag. Tags that do not require a closing tag are referred to as
'self-closing' tags.

- An opening paragraph tag: `<p>`
- A closing paragraph tag: `</p>`

Most tags in HTML have default CSS properties which affect how the content inside the tag is
presented on the page.

#### What is an attribute in HTML?

Attributes allow you to customise tags. Where tags require opening and closing tags, attributes are
declared on the opening tag. For example:

```html
<td colspan="4">This is a table cell</td>
```

The first attribute you will use in your HTML document is to declare the language attribute on the
`<html>` tag, like so:

```html
<html lang="en">
  <!-- the rest of your HTML document -->
</html>
```

Attributes on self-closing tags are declared in the same way.

```html
<img src="image.png" alt="This is the alternative text attribute value" />
```
