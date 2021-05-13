# rtsp-server
RTSP server from mp4 file

## Usage

Put the video of interest inside the `videos` folder
Write the video filename and the stream name in the `docker-compose.yml`

Run the server:
1. `cd docker`
2. `docker-compose up --build -d`

Use it, e.g.,:
`rtsp://server-ip:8554/stream1`
