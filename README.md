### elasticsearch-py
---
https://github.com/elastic/elasticsearch-py

https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html


```py
// test_server/test_client.py
from __future__ import unicode_literals

from . import ElasticsearchTestCase

class TestUnicode(ElasticsearchTestCase):
  def test_indices_analyze(self):
    self.client.indices.analyze(body='{"text": "xxx"}')
```

```
```

```
```
