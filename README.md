# Smokey Testy

Simple smoke test action


### Usage

Just provide a comma separated list of URLs to test

```yaml
jobs: 
  steps:
    - name: Run smoke tests
      uses: @action/smoke-testy
      with:
        - urls: 'https://example.com/a,https://example.com/b'
```

Output:
