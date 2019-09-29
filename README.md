# codemirror-theme-github

A CodeMirror theme inspired by the GitHub editor.

## Installation

```
npm install codemirror-theme-github --save
```

## Usage

1. Import the CSS file into your application:

    ```css
    @import "codemirror-theme-github/theme/github";
    ```

2. Tell CodeMirror to use it:

    ```js
    const editor = CodeMirror(document.body, {
      mode: 'javascript',
      lineNumbers: true,
      theme: 'github',
    });
    ```