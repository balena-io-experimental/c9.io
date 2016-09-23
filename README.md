# c9.io

Guide to using [c9.io](https://c9.io) for getting started guides and workshops, [c9.io](https://c9.io) makes it super simple to create and use SSH keys which is a massive bonus.

## Resin c9.io account
Set up a single c9.io account
 - Go to [c9.io](https://c9.io)
 - Set up an account
 - Add the education plan for $1 a month

## Participant c9.io account
Set up a participant c9.io account for each user
 - Invite participant to the resin c9.io account using their email
 - Have them set up the account before the workshop

## Participant resin.io account
Set up a participant resin.io account for each user
 - Have the participant set up a [resin.io](https://dashboard.resin.io/signup) account before the workshop, they could follow the [getting started guide](http://docs.resin.io/raspberrypi/nodejs/getting-started/)
 - Have them add their c9.io SSH key to resin.io and Git
     - Go to [c9 SSH settings](https://c9.io/account/ssh)
     - Copy second key, under `Connect to your private git repository`
     - Add key to [resin.io](https://dashboard.resin.io/preferences?tab=sshkeys)
     - Add key to [Git](https://github.com/settings/ssh) (optional)

## Participant c9.io workspace
Create a workspace
 - Log into [c9.io](https://c9.io)
 - Create a new workspace
     - Give it a name
     - Give it a description
     - Clone a starting repository (optional)
     - Choose a language (optional)

Set up the workspace
 - Install resin CLI `$npm i -g resin-cli`
 - Add the resin git remote endpoint `$git remote add resin charlie1@git.resin.io:charlie1/myfleet.git`

Devlopment workflow
 - Develop and push with `git push resin master`
 - Iterate quickly with `resin sync`
