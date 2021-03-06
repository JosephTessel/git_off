# git_off
**Purpose:** Maintain that meaningless streak with a git code queue!

**Use:** Similar to git except files or directories you add are put into a queue. Once a day, an item from the queue is committed and pushed up to the remote repo

**Install:**

1. Clone / download repo
2. `cd` into repo
3. run the install file: `./install.sh`
4. use git_off the same way you would `git`: `git_off` *some command*

##Available commands

- `add -A`              add directory
- `add .`               add directory
- `add filename`        add file
- `commit -m "message"` commit message
- `status`              display current queue
- `log`                 display log of successful commits
- `log -e`              display error queue log (aka unsuccessful commits)
- `log --clear`         clear log
- `log -e --clear`      clear error queue log
- `rm queue_id`         remove an item from the queue
- `ll`                  display last item added to queue'


## TODO / Current issues:

1. Linux (and possible Mac) issue. SSH keys are not accessible to cron job. Git `push` and `pull` fail.  
