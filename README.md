# FFMPEG-Download
How to download videos via FFMPEG


Apple WWDC2019 download

In order to download the keynote as an mp4 file run this ffmpeg command in Terminal:
ffmpeg -i https://p-events-delivery.akamaized.net/3004qzusahnbjppuwydgjzsdyzsippar/vod3/8500/8500_vod.m3u8 -c copy -bsf:a aac_adtstoasc Apple_WWDC2019_main.mp4
