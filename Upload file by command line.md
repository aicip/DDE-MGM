# Upload files to Bitbucket via command line

## Pre-requisite
* git (installed on the AICIP work station)

An easy way is to remote the work station

## Upload a file to an existing repo
1.Copy the *URL* of the repo

2.Clone the repo to local
```
$ git clone URL
```

3.Enter the local repo directory
```
$ cd repo
```

4.Add new files to the local repo

5.Stay in the directory of local repo, sync the local repo to the sever

```
$ git add --all
$ git commit -m 'message'
$ git push
```

Please modify the mesage to your name or any useful information.
Then account name and password may be required.
