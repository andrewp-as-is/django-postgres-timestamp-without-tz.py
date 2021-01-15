<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-postgres-timestamp-without-tz.svg?maxAge=3600)](https://pypi.org/project/django-postgres-timestamp-without-tz/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-postgres-timestamp-without-tz.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-postgres-timestamp-without-tz.py/actions)

### Installation
```bash
$ [sudo] pip install django-postgres-timestamp-without-tz
```

#### Examples
```python
from django.db import models
from django_postgres_timestamp_without_tz import DateTimeWithoutTZField

class Model(models.Model):
    created_at = DateTimeWithoutTZField()
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
