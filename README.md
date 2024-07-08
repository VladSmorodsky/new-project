# New Project
Creating repository steps:
1. Create repository on [GitHub](https://github.com/).
2. Initiate git repository locally:
```shell
git init
```
3. Add configs:
```shell
git config --global user.name "username"
git config --global user.email "username@example.com"
```
4. Create README.md file and add it:
```shell
git add README.md
```
5. Commit the file with message:
```shell
git commit -m "init"
```
6. Connect with remote repository:
```shell
git remote add origin git@github.com:account_name/new-project.git
```
7. Push changes:
```shell
git push -u origin main
```
8. Create development branch and use it for work:
```shell
git checkout -b development
```
9. Make changes, check it and add:
```shell
git add .
```
10. Commit changes:
```shell
git commit -m "added changes"
```
11. Push to repository:
```shell
git push origin development
```
12. In the github repo, create the PR, check it and merge into main branch