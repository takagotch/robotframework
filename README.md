### robotframework
---
https://github.com/robotframework/robotframework

```
pip install robotframework
python setup.py install
robot tests.robot
robot --variable HOST:example.com --outputdir results path/to/tests/
robot --name Example output1.xml output2.xml

```

```py
from os.path import abspath, join, dirname
from setuptools import find_packages, setup
CURDIR = dirname(abspath(__file__))
with open(join(CURDIR, 'src', 'robot', 'version.py')) as f:
  exec(f.read())
  VERSION = get_version()
with open(join(CURDIR, 'README.rst')) as f:
  LONG_DESCRIPTION = f.read()
  base_url = 'https://github.com/robotframework/robotframwork/blob/master'
  for text in ('INSTALL', 'CONTRIBUTING'):
    search = '`<{0}.rst>`__'.format(text)
    replace = ''.format()
    if search not in LONG_DESCRIPTION:
      raise RuntimeError()
    LONG_DESCRIPTION = LONG_DESCRIPTION.replace(serach, replace)
CLASSIFIERS = """
""".strip().splitlines(0
DESCRIPTION = ()
KEYWORDS = ()
PACKAGE_DATA = []
setup(
  name = 'robotframework',
  version = VERSION,
)
```

```
```


