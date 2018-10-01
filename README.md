# Mehub

a Command line app for showing Github User's Information

### Todo
- add testing

### Install

Make sure Elixir is installed on your computer https://elixir-lang.org/install.html

- Clone mehub
- Build mehub
```shell
$ make install
```

### Usage

`./mehub -u 'github_username'`

- Show Github user's information
```shell
$ ./mehub -u tj

* Name : TJ Holowaychuk
* Followers : 37107
* Website : https://apex.sh
* Bio : Founder of Apex
https://apex.sh, a non-startup.
medium.com/@tjholowaychuk • twitter.com/tjholowaychuk • tjholowaychuk.com
* Location : Victoria, BC, Canada
* Company : Apex
```

- Show Github user's organization
```shell
./mehub -u tj -o

tj's Organization :
* zeromq
* LearnBoost
* senchalabs
* component
* koajs
* slate
* clibs
* reworkcss
* expressjs
* cojs
* nanodb
* jstrace
* statsd
* gohttp
* visionmedia
* apex
```
#
### Author
Wuriyanto https://github.com/wuriyanto48