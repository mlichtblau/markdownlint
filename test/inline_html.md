# Regular heading

<h1>Inline HTML Heading {MD033}</h1>

<p>More inline HTML {MD033}
but this time on multiple lines
</p>

    <h1>This shouldn't trigger as it's inside a code block</h1>

```text
<p>Neither should this as it's also in a code block {MD046:11}</p>
```

## Elements in code spans

Text `<code>` text \` text
Text \` text `<code>` text
Text \` text \` text `<code>` text
Text \` text `<code>` text `<code>` text
Text \` text `<code>` text \` text `<code>` text
Text \`\` text `<code>` text
Text `<code>` text \` text `<code>` text

## Slash in element name

Text **\<base directory>\another\directory\\<slash/directory>** text
