Save `workspace_utils.py` into your notebook's directory. 

Then in your notebook run:

```import workspace_utils.py```

and use it to wrap your long running code, as shown below:

```
from workspace_utils import active_session
 
with active_session():
    # do long-running work here
```

You can also cut and paste the code into a new file from the raw link for this file. Make sure you call the file `workspace_utils.py`.
