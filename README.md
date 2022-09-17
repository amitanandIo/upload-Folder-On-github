# upload-Folder-On-github


## Copy repository from local to Remote
<ul>
<li><a>git config --global user.name "amitanandIo"</a></li>
<li><a>git config --global user.email amita.ic.19@nitj.ac.in</a></li>
  go to remote repository and copy thier code.
  goto local repository and in document /open git bash here by right click.
  type following command.....
  git clone repository url
  insert all folder in this newly created folder.
  open git bash here again
<li><a>git init</a></li>
<li><a>git add .</a></li>
<li><a>git commit-m "updating"</a></li>
<li><a>git push -u origin main</a></li>
</ul>


## Host Website on Github
  Condition are:-
1. repository name must be in format of "file_Name.github.io"
2. repository must contain index.html 
3. go to setting -> pages -> change the branch from none to main;
   save it.
4. wait for max 3 min. 
5. Finally , u will get the link.

## Error like..
support for password authentication was removed on august 13, 2021. remote: please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.

then , go to github account.
goto setting/Developer option / create a new token and tick all unchecked token .save expiry duration is infinite.
after that copy the token and paste inplace of password.
`username` :- amitanandio
`token` :- paste the token command here
problem solved.
