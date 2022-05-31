# git-deploy

- Include a README file <br>
 $echo "git-deploy" >> README.md

- Initialize git <br>
 $git init

- Add files <br>
 $git add -A

- Commit to repo <br>
 $git commit -a -m "first commit"

- Shift to the desired branch <br>
 $git branch -M Maestro

- Add a remote <br>
 $git remote add [remote_name] [remote_url]<br>
 $git remote add second https://github.com/evansmbithi/git-deploy.git

- Push to remote repository on the specific branch <br>
 $git push [remote_name] [branch_name] <br>
 $git push second Maestro
