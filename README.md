# cradle-lib-config

Public Cradle config library.

```text
configs/
  <config>/
    ansible/<config>.j2
    files/
```

This repository contains reusable configs that are intended to be safe to use
from any scenario. Scenario-specific decoys and applications belong in the
scenario library; once a component has been generalized and reviewed here, any
scenario may reuse it.
