# Simple command line password generator

A simple command line password generator that copies a newly created random password to the pasteboard. Built and used regularly on MacOS. With other OSs YMMV.

## Installation

### Prerequites
At time of writing I think [Jot](http://support.moonpoint.com/os/os-x/man/jot.html) comes with MacOS as default. if not, you'll need to install that.

### Install
Check out this repo to your local host and copy the file _password_ somewhere on your PATH. For example:

```shell
cp password /usr/local/bin/password
```

Make it executable:

```shell
chmod 755 /usr/local/bin/password
```

## To run
Open a terminal and run the command 

```shell
$ password
Password is on your pasteboard
```

You'll find that you can then paste this nice new password anywhere you like.

## Modifications
If you'd like added security, uncomment the section of the password file that will overwrite the pasteboard after 30 seconds
