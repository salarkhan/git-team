#Git-Pear

A simple utility for sharing credit for commits while working on teams.

##Installation
```
git clone https://github.com/salarkhan/git-pear.git
cd git-pear
./install
```

##Usage
```pear``` followed by any number of email addresses.
Committers and commit authors will cycle through this list between each commit.

``` bash
pear example1@email.com example2@email.com
```

To quit, simply type `pear` with no arguments
```
pear
```

##Authentication
Upon team creation, Pear pings GitHub's API to retrieve each member's full name. 
If you expect your IP address to be making more than 60 unauthenticated requests an hour, Pear optionally accepts an  API token. To authenticate, [generate a token via GitHub](https://help.github.com/articles/creating-an-access-token-for-command-line-use) and export it as an environment variable in your `bash_profile`
```
export GIT_API_TOKEN=21231381thisis1231a123github123token8
```


##Examples!
```
The result on Github 
```
![github gui](https://cloud.githubusercontent.com/assets/3118416/4260962/539cbe56-3b57-11e4-8ffd-3cef13ac32cb.png)

```
Using pear on a brand new repo
```
![pear init](https://cloud.githubusercontent.com/assets/3118416/4260961/417ac312-3b57-11e4-9724-634c2b75f134.png)
