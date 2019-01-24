Save `workspace_utils.py` into your notebook's directory. 

Then in your notebook run:

```import workspace_utils.py```

and use it to wrap your long running code, as shown below:

```
from workspace_utils import active_session
 
with active_session():
    # do long-running work here
```

You can also cut and paste the code from the "raw" view of the `workspace_utils.py` file in this directory into a new file, instead of cloning this repo. Make sure you name the new file `workspace_utils.py`.
