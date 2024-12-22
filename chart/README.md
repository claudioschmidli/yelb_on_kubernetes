# Yelb Helm Chart

Helm template rendering:
```bash
helm template yelb . -f values.yaml
```

Installation:
```bash
helm upgrade -i yelb . \
  -n project-participant17 \
  -f values.yaml
```