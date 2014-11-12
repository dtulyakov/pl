mkdir /path/to/your/project
cd /path/to/your/project
git init
git remote add origin git@bitbucket.org:dtulyakov/pl.git

echo "Denis Tulyakov" >> contributors.txt
git add contributors.txt
git commit -m 'Initial commit with contributors'
git push -u origin master

#######################
cd /path/to/my/repo
git remote add origin git@bitbucket.org:dtulyakov/pl.git
git push -u origin --all # pushes up the repo and its refs for the first time
git push -u origin --tags # pushes up any tags