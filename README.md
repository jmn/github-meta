# Github Meta
## References
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

## Github Markdown
### Diff language
```diff
+ this will be highlighted in green
- this will be highlighted in red
```
### Example code block: Ruby
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
### Tabular data
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

### Tabular data with formatting
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

### Blockquote
> Whatever this is
> suppose to say.

### Definition list
<dl>
  <dt>Term</dt>
  <dd>definition</dd>
</dl>

### Image
<a><img src="http://dump.thecybershadow.net/6c736bfd11ded8cdc5e2bda009a6694a/colortext.svg"/></a>

### Another image
<img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Glider.svg"/>
