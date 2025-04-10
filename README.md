# Hello World Action

This is a reusable GitHub Action that prints "Hello, <name>!".

## Inputs

- `name`: The name to greet (default: "World").

## Example Usage

```yaml
- uses: <your-username>/hello-gha@v1
  with:
    name: "GitHub"
