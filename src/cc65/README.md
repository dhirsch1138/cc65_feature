
# CC65 Development Package

A feature implementing cc65 for the 6502

## Example Usage

```json
"features": {
    "ghcr.io/dhirsch1138/cc65/cc65:1": {
        "version": 1,
        "firmwarepath": ".cc65/firmware/",
        "sourcepath": "source/"
    }
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| firmwarepath | What path will the firmware.cfg file be? | string | ".cc65/firmware/" |
| sourcepath | What path will the source files be in? | string | "source/" |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/devcontainers/feature-starter/blob/main/src/hello/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
