# Dummy

A minimal dummy chart used for testing Helm packaging and index generation.

## Installation

```bash
helm repo add example https://mridang.github.io/example-helm
helm install dummy example/dummy
```

## Configuration

### Values

<!-- render.chart.valuesTable -->
| Key | Type | Default | Description |
|-----|------|---------|-------------|
| foobar | int | `1` |  |
| replicaCount | int | `1` |  |
<!-- end.chart.valuesTable -->
