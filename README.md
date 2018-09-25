# music-library-api

We will be using a hosted database provider called Mlab this week.
They offer a free tier solution where we can create a MongoDb database and use it with our Express API.
Once you've an Mlab account and a MongoDb database set-up. We'll implement a REST API which will let us do the following.

Steps
CRUD actions on artist, album and songs.

Getting started with Mlab, Mongoose and Express. step1

Create an artist profile. POST /artist. step2

Get a list of all artists within our library. GET /artist step3

Get a specific Artist information using their unique Artist ID. GET /artist/:artistId step3

Testing the API step4

Update an artist profile. PUT /artist/:artistIdstep5

Delete an artist profile. DELETE /artist/:artistIdstep6

Record album information for an artist. POST /artist/:artistId/albumstep7

Refactor albums into their own collection. step8

Add song information to an album. POST /album/:albumId/song step9

List all albums by an artist GET /artist/:artistId/albums step10



Exemplar


Bonus Steps - Without the walkthrough.

List all songs by an artist GET /artist/:artistId/songs - Query the Song collection for all songs where artist is equal to the artistId parameter from the request body.
Update a song PUT /song/:songId - Update a song in the Song collection. This will be similar to step5.
Delete a song DELETE /song/:songId - Delete a song from the Song collection. This will be similar to step6.
