# Excercise: Playtracker

In Netflix or Spotify for example you have timelines of your content.
Ideally if you need to stop playing the content you can continue watching it from the same point later and even with a totally different device.


![](https://user-images.githubusercontent.com/608642/34182396-bdcbacd2-e51e-11e7-9df1-56141464535a.png)

However this can be cubersome to implement because you always have to send it first before it's accessible for other devices.

Solution to handle situations where the user might close the content playing website or application in any moment is to send periodically the current position of the player.

This is effective but it also generates lots of writes.

## Calculation of generated load

Let's say if we're sending every five second an update of the position so we could be only maximum on 5 seconds late with the 'saved' position.

With very busy site we might have over 20k updates every second.
That's more than most relational databases in cloud environments can handle so for that we need to use something more suitable for the hard write load.

## Requirements

Essentially we have 3-tuples coming in `(user_id, content_id, position)` and we need to answer queries about latest update as fast as possible.

## Task

Build a microservice for providing two APIs for updating and fetching the current position by content_id and user_id

All implementation details are free.


## Technology recommendations:
Try out Cassandra or Redis
