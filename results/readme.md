# folder for results

´´´
 ffmpeg -framerate 15 -i 03_image_%6d.png -c:v libx264 -profile:v high -crf 20 -pix_fmt yuv420p output.mp4
´´´
