# NodeStream

NodeStream is an easy to use open-source application that allows people to stream using OBS to a remote server.

To setup download this as a zip file, remix it on Glitch, or use git to clone the repository.

__Downloading__

Once you have downloaded it run these two commands:

`npm i`

`node .`

Then, you open OBS and set the stream type to custom

Set the streaming url to `rtmp://localhost:81/live` and set the stream key to what you want to call the stream.

Then, start streaming and go to `http://localhost:81/live/[STREAM_NAME].flv`

__Glitch__

https://glitch.com/edit/#!/remix/nodestream-wiresdev

Open OBS and set the stream type to custom

Set the streaming url to `rtmp://localhost:81/live` and set the stream key to what you want to call the stream.

Then start streaming and go to `http://localhost:81/live/[STREAM_NAME].flv`
