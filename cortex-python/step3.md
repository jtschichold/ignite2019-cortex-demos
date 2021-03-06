Now you are ready to use the Cortex Python SDK!

You can query the Cortex Data Lake using the Logging Service API and using query
syntax really similar to SQL. In the included script `hello_world.py` we will execute
the following query:

`select dst, app, misc, name-of-threatid from panw.threat where subtype='wildfire-virus' limit 5`

To check how the SDK works open the script in the editor `hello_world.py`{{open}}

Execute the script from the command line: `./hello_world.py`{{execute}}

If everything is correct you should see the JSON dump of the last 5 wildfire events
recorded in your data lake.

If you are more interested in endpoint events, go ahead and change the script
to query Traps events:

`select messageData from tms.analytics limit 1`
