# Notes on using Github

The easiest way to get the commands needed for initializing and using a git repository are to just create a new empty repository. Do not select any of the options. Then, on the local computer:

```
git clone 'https://github.com/username/project'
```

## Create a new repository

Press the green new button.

![Create New Repo](../img/2020-07-05 14_07_26-GitHub.png)

Do not select any options. This will create an empty repo.

![Empty Project](../img/2020-07-05 14_08_35-Create a New Repository.png)

The next page of the setup shows all the commands needed for setting up the repo from a command line.

![Commands 1](../img/2020-07-05 14_09_29-reesehaywood_helloworld.png)
![Commands 2](../img/2020-07-05 14_09_53-reesehaywood_helloworld2.png)

## Continue working on a project

In the local directory:

```
git checkout master
```

Then:

```
git pull
```

## General workflow

Iterate over the following steps to keep the repo updated remotely.

```
git add --all
```

```
git commit -m 'Message for commit'
```

```
git push -u origin master
```

I am not sure how this works over a long time. I think as long as I don't change the master on the GitHub site I don't have to keep checking it out. My local copy will remain the master.

