# Custom Greeting Action

A custom JavaScript action created for Lab 05 that greets someone and returns the current time.

## Inputs

- `who-to-greet`: Who to greet (default: 'World')

## Outputs

- `time`: The time when the greeting was made

## Example Usage

```yaml
- uses: jhaindev/my-custom-action@v1
  with:
    who-to-greet: 'Mona'
```
