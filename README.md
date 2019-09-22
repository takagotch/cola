### cola
---
https://github.com/chineking/cola

```py
// tests/test_master_worker.py
import unittest
import tempfile
import os
import shutil
import errno
import time

import yaml

from cola.core.utils import_job_desc
from cola.core.zip import ZipHandler
from cola.context import Context

class Test(unittest.TestCase):
  
  def setUp(self):
    self.working_dir = tempfile.mkdtemp()
    self.job_dir = os.path.join(self.working_dir, 'master', 'jobs')


```

```
```

```
```


