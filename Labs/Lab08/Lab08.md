## Part 1 Answers

- Make sure infinity is in your Lab08 folder in GitHub

## Part 2 Answers

1. Getting started
   - Command to find the PID:"ps $$"
   - PID of "Terminal A":"1263"
   - PID of "Terminal B":"1450"
2. Using `./` to run `infinity` in Terminal B
   - PID of script:"14412"
   - Command to kill script:"kill 14412"
   - Effects of running the script:"You cannot use the script running command takes over Terminal B."
3. Using `source` to run `infinity` in Terminal B
   - PID of script:"1466"
   - Command to kill the script:"kill -9 1466"
   - Effects of killing the script:"Terminal B was terminated"
4. Running `infinity` as a background job in Terminal B
   - Command to run script in background:"./infinity.sh &"
   - Job ID of script:"job id, 1569"
   - PID of script:"1569"
   - Command to kill script via job id:"kill -9 1569"
   - Effects of exiting terminal:"Yes, Still running, the & made the job to start as background job"
5. Run `infinity` in a `screen` or `tmux` session
   - Command(s) to run `infinity` in a screen session:"i.screen -dmS myScreenSession (create a screen)
ii. screen -d -m -t myScreenSession sh infinity.sh (runs infinity in the session)"
   - Detach from `screen` / `tmux` session:"screen -d <myScreenSession>"
   - Command to show `screen` / `tmux` sessions:"screen -list"
   - Effects of exiting terminal:"Yes, still running. When I closed the terminal, the screen becomes detached but still active. As such, infinity.sh kept running since the environment was still enabling."
   - Command / steps to kill the `screen` / `tmux` session:" i. screen -r myScreenSession (Reattach the screen)
ii. exit. (Terminates it)"

## Part 3 Answers

1. "git checkout -b updates
2. "git checkout -b updates" This command automatically switched me to the new branch
3. "vim infinity.sh" used # to add comments
4. "git push --set-upstream origin updates"
5. Confirmed? Yes it was confirmed
6. "git checkout main"
7. "git merge main"
8. "git push --set-upstream origin main"
9. Confirmed? Yes it was confirmed
10. Use "git branch" where it will show the branches and the one that is highlighted green is the current branch that you are on.
