# Project streaming-poc

This is a proof of concept project of a streaming websocket using a priority queue and "async processor" of video data.

## Getting Started

As of now, there's nothing, but soon will be.


## Roadmap

### Back

[ ] Stream-load video in memory
[ ] Process in chuncks based in size
[ ] Send chuncks to the pqueue
[ ] Use the pqueue to correctly order it
[ ] Send to the websocket as needed, with overlap

### Front

[ ] Load video correctly
[ ] Order video as it should be 
[ ] Decompress
[ ] Play
[ ] Cache it for a while (duration times 2?)

