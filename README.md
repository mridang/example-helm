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
| podAnnotations | object | `{}` | Extra pod annotations |
| podLabels | object | `{}` | Common pod labels |
| replicaCount | int | `1` | Number of replicas to deploy |
<!-- end.chart.valuesTable -->
