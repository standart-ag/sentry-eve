# Sentry Eve support

Easy to use package for Eve framework with support for Sentry

## Install

```bash
pip install sentry-eve
```

## Configuration

`SENTRY_DSN` - Your sentry DSN url

Add it in your `settings.py`:
```python
SENTRY_DSN = "<Your sentry dsn url>"
```

## Use
```python
from SentryEve import SentryEve

app = SentryEve(__name__)
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Copyright

This software is developed inside Standart AG, LLC, 2019