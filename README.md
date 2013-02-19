# OW2 Play Event Platform

> Community website for the Play Event Platform.

## Run

- Download Jekyll at jekyllrb.com and run 'rake start'
- Install some gems if not already installed:

    sudo gem install net-ssh
    sudo gem install net-scp

## Generate

To generate the site, launch 'rake generate'. The site is generated under the _site folder.

## Deploy

To deploy to play.ow2.org, launch 'rake deploy ow2login=YYY ow2password=XXX'. Ask the credentials to @chamerling if needed...
In the better case, the website is deployed automatically by a jenkins server and you do not have to do this yourself.

@chamerling