# URLockBox

# README

## Summary
URLockBox is a handy web app that allows you to add links and track their read status.
Try it out [here](https://urllockbox-jg.herokuapp.com/)!

## To Clone: 

`git clone git@github.com:glassjoseph/m4-final-starter.git`
`cd m4-final-starter`
`bundle install`

## To Set Up Database:
`rake db:create`
`rake db:migrate`
`rake db:create`


## To run the test suite:
`rspec`


## Hot Reads Service:

URLockBox is integrated with a Hot Reads backend service which tracks link reads and provides polularity info. Check out its repo [here](https://github.com/glassjoseph/hot_reads).


| Verb        | URL           | Action  |
| ------------- |-------------| -----|
| GET     | https://hotreads-jg.herokuapp.com/api/v1/reads| Returns a json formatted list of top ten links, ordered by popularity |
| POST      | https://hotreads-jg.herokuapp.com/api/v1/reads?url=your_link_here     |   Creates a read record of your_link |
