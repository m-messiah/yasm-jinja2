# YASMJinja2

*Jinja2 is a full featured template engine for Python. It has full unicode support, an optional integrated sandboxed execution environment, widely used and BSD licensed.*

This is a plugin for TextMate and Sublime Text editors adding support of Json-compatible Jinja2 templates syntax.
YASMJinja2 uses `<` brackets instead of `{`, for example:
```
<% for i in range(10) %>
<% if i % 2 %> <# just for odd numbers #>
Step << i >>.
<% endif %>
<% endfor %>
```
