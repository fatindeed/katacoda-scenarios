The `cisco_ios_to_git.py` Python script has some variables you need to define.

Edit `host`, `username` and `password` to match your device. By default the connection details are for the DevNet IOS-EX Sandbox mentioned above.

`sed -i 's!10.10.20.48!sandbox-iosxe-latest-1.cisco.com!g' cisco_ios_to_git.py`{{execute}}

Edit `git_repo_url` to match your Git repository URL.

Optional - edit `commit_message` to specify what Git should use as the message for each commit.
