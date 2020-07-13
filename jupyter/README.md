Save `workspace_utils.py` into your notebook's directory. 

Then in your notebook wrap your long running code with `active_session`, as shown below:

```
from workspace_utils import active_session
 
with active_session():
    # do long-running work here
```

You can also get `workspace_utils.py` directly from a Jupyter terminal like so:
```
curl -O https://raw.githubusercontent.com/udacity/workspaces-student-support/master/jupyter/workspace_utils.py
```
