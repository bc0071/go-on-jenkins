###

0. Create a directory, "go-on-jenkins"
```shell
  $ take go-on-jenkins
```
1. Create Jenkinsfile

2. Create main.go

3. Git initialize
   Create a repository 'go-on-jenkins' on GitHub
```shell
    echo "# go-on-jenkins" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/bc0071/go-on-jenkins.git
    git push -u origin master

```
4. Install "Go plugin" in Jenkins

5. Cofigure Go as global tool
```jenkins
  Jenkins -> Manage Jenkins -> Global Tool Configuration
    Name: go-1.12
    [x] Install automatically
    Install from golang.org
    version: Go 1.12
 ```

6. Enhance Jenkinsfile

7. Add/Commit/Push
```shell
  $ git add .
  $ git commit -m "go-on-jenkins 1st commit"
  $ git remote add origin https://github.com/bc0071/go-on-jenkins.git
  $ git push -u origin master
```




