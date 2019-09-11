# open-in-vscode

Instructions for creating an "Open in VS Code" button

## URL

```
vscode://vscode.git/clone?url=${git URL}.git
```

Example:

```
vscode://vscode.git/clone?url=git@github.com:google/clasp.git
```

TODO: Create a GCF VS Code redirect.

<a href="https://us-central1-serverless-com-demo.cloudfunctions.net/redirect">Open in VS Code</a>

## Prerequisites

- [VS Code](https://code.visualstudio.com) must be installed.
- Set `Git: Default Clone Directory` to `~/Documents/github`
