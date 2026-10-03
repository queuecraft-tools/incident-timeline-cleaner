# incident-timeline-cleaner

Normalize incident notes into a consistent event timeline.

## Run

Requires Go 1.22+.

```sh
go run .
```

The tool reads its development gateway settings from `config/development.json`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.

## Model

This example targets the `claude-opus-5-5` frontier model through the configured OpenAI-compatible router.
