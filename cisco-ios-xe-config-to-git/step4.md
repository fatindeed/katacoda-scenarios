To run the Python script

`python cisco_ios_to_git.py`{{execute}}

### Check the result

The script automatically deletes all created files after the Git push is complete. This means there's nothing to see locally after it has ran.

Go to your remote Git repository and you should see your config uploaded.

If you make changes to the switch config and re-run the Python script, you will see Git track the changes between the new config and the old config. Check the changes by viewing the most recent Git commit!