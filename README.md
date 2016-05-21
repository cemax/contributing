# Contribution Instructions

## 1. Fork the repository
1. Open in a new tab the repository you want to contribute.
2. In the top-right corner of the page, click the Fork button.

## 2. Clone the forked repository
1. On GitHub, navigate to your fork.
2. In the right side of your fork's repository page, copy the clone URL.
3. Open a terminal, copy and paste the commands below.
4. Rename `<username>` below to your github username.
5. Rename `<repository>` below to the forked repository name.
6. Hit enter to execute the commands.

```
cd ~/Downloads
git clone git@github.com:<username>/<repository>.git
cd <repository>
```

## 3. Set upstream URL
1. Open a terminal, copy and paste the command below.
2. Rename `<repository>` below to repository name.
3. Hit enter to execute the commands.

```
git remote add upstream git@github.com:cemax/<repository>.git
```

## 4. Create a feature branch
1. Open a terminal, copy and paste the command below.
2. Replace `<branch>` with your feature branch name.
3. Hit enter to execute the commands.

```
git checkout -b <branch>
```

## 5. Make your contribution in the feature branch

```
echo "make your changes"
```

## 6. Check for changes
Open a terminal, copy and paste the commands below and hit enter.

```
# if any file(s) is added
git status
# changes inside the files
git diff
```

## 7. Commit your changes
Open a terminal, copy and paste the command below and hit enter.

```
git commit -am "contribution description"
```

## 8. Pull new commits from upstream
Open a terminal, copy and paste the command below and hit enter.

```
git pull upstream master
```

## 9. Push your changes to your remote repository
1. Open a terminal, copy and paste the command below.
2. Replace `<branch` with your feature branch name.
3. Hit enter to execute the commands.

```
git push origin <branch>
```

## 10. Create a pull request.
1. Go to github and navigate to your repository.
2. Switch to your feature branch.
3. Click the compare & review button.
4. Review the pull request.
5. Press create pull request button.
