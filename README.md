![Shout Client](http://i.imgur.com/baQjLOql.png)
# What's this?

This branch contains sources for manual build Shout client!

# Build instructions
Firstly, for build, you need to install packages for build (nodejs, npm). Please, run these commands *FROM ROOT*!
For Ubuntu:
```bash
apt install nodejs npm build-essential -f -y
```
For CentOS:
```bash
yum install epel-release
yum install nodejs npm
```

Secondly, you need to grab our sources. Run these commands you can without root access.
```bash
git clone https://github.com/limenv/shout
cd shout
```
Thirdly, build it :)
```bash
npm install 
```
For run, run:

```bash
npm start
```



