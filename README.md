# docker-cfn-python-lint

Docker container for running Python [cfn-lint](https://github.com/awslabs/cfn-python-lint) using Docker.

Usage:
```
docker run --rm -v $(pwd):/code -w /code temyers/cfn-python-lint path/to/my/template
```
