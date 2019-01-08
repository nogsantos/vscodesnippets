# VSCode snippets

Code snippets are templates that make it easier to enter repeating code patterns, such as loops or conditional-statements.

## Setup

Use the bash to setup.

Depending on your plaform, your user snippets file is located here:

- Windows `%APPDATA%\Code\User\snippets\(language).json`
- Mac `$HOME/Library/Application Support/Code/User/snippets/(language).json`
- Linux `$HOME/.config/Code/User/snippets/(language).json`

### Javascript

<table>
  <tbody>
    <tr>
      <th>Command</th>
      <th>Descriptio</th>
    </tr>
    <tr>
      <td>clg</td>
      <td>Console log</td>
    </tr>
    <tr>
      <td>clw</td>
      <td>Console warn</td>
    </tr>
    <tr>
      <td>cli</td>
      <td>Console info</td>
    </tr>
    <tr>
      <td>cle</td>
      <td>Console error</td>
    </tr>
  </tbody>
</table>

#### Features

- [Consoles](https://developer.mozilla.org/en-US/docs/Web/API/Console)

##### Linux

```bash
$ ln -fs ~/apps/vscodesnippets/javascript.json ~/.config/Code/User/snippets/
```

##### Mac

```bash
$ ln -fs ~/apps/vscodesnippets/javascript.json $HOME/Library/Application\ Support/Code/User/snippets/
```

### Markdown

<table>
  <tbody>
    <tr>
      <th>Command</th>
      <th>Descriptio</th>
    </tr>
    <tr>
      <td>msb</td>
      <td>Bash code tags</td>
    </tr>
    <tr>
      <td>msj</td>
      <td>Java code tags</td>
    </tr>
    <tr>
      <td>msjs</td>
      <td>JavaScript code tags</td>
    </tr>
    <tr>
      <td>msc</td>
      <td>Css code tags</td>
    </tr>
  </tbody>
</table>

##### Linux

```bash
$ ln -fs ~/apps/vscodesnippets/markdown.json ~/.config/Code/User/snippets/
```

##### Mac

```bash
$ ln -fs ~/apps/vscodesnippets/markdown.json  $HOME/Library/Application\ Support/Code/User/snippets/
```

##### References

- [Visual studio code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
- [Read the Docs](https://vscode-docs.readthedocs.io/en/stable/customization/userdefinedsnippets/)
