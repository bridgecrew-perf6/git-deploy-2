# git-deploy

- Include a README file
- $echo "git-deploy" >> README.md

- Initialize git
- $git init

- Add files 
- $git add -A

- Commit to repo
- $git commit -a -m "first commit"

- Shift to the desired branch
- $git branch -M Maestro

- Add a remote 
- $git remote add [remote_name] [remote_url]
- $git remote add origin https://github.com/evansmbithi/git-deploy.git

- Push to remote repository on the specific branch
- $git push [remote_name] [branch_name]
- $git push origin Maestro
