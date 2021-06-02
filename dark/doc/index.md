```js script
import { html } from 'lit-html';
import '../src/colors.scss';
```

```html:html
<h1>Colors</h1>
<table  cellpadding="2">
<tbody>
<tr>
<td><p style="color:var(--background-body)">--background-body</p></td>
<td><p style="color:var(--background)">--background</p></td>
<td><p style="color:var(--background-alt)">--background-alt</p></td>
</tr>
<tr>
<td><p style="color:var(--text-main)">--text-main</p></td>
<td><p style="color:var(--text-main)">--text-main</p></td>
<td><p style="color:var(--text-bright)">--text-bright</p></td>
</tr>
<tr>
<td><p style="color:var(--text-muted)">--text-muted</p></td>
<td><p style="color:var(--links)">--links</p></td>
<td><p style="color:var(--focus)">--focus</p></td>
</tr>
<tr>
<td><p style="color:var(--border)">--border</p></td>
<td><p style="color:var(--code)">--code</p></td>
<td><p style="color:var(--button-hover)">--button-hover</p></td>
</tr>
<tr>
<td><p style="color:var(--form-placeholder)">--form-placeholder</p></td>
<td><p style="color:var(--form-text)">--form-text</p></td>
<td><p style="color:var(--variable)">--variable</p></td>
</tr>
<tr>
<td><p style="color:var(--highlight)">--highlight</p></td>
<td><p style="color:var(--scrollbar-thumb-hover)">--scrollbar-thumb-hover</p></td>
</tr>
</tbody>
</table>
```
