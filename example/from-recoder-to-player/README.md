# Test sending audio signal from recoder to player 

Start from project root

1. Install dependencies
   
   `sudo apt-get install libasound2-dev`

2. Start player
   
   `go run cmd/player/main.go`

4. Start recoder
   
   `go run cmd/recorder/main.go`

5. Start test server

   `go run example/from-recoder-to-player/server.go`