# VideoFormatConverter-ffprobe-ffmpeg
 
To create a programme to analyse the films' format and, if necessary, convert them, automating the whole process.

The application needs to adhere to the following standards: 
1. The programme needs to run on a Python-written Jupyter notebook, examine the files using ffprobe, and convert the videos using ffmpeg. 
2. The application should produce a brief TXT report from a set of video files listing which movies don't adhere to the festival's digital format requirements and what the "problematic" fields are. 
3. The software should automatically convert any films submitted that are in the wrong format. By appending '_formatOK' to the end of the name, the programme will generate a new copy of the movies. 
4. The festival's organisers have specified the following as the film's format:
- Video format (container): mp4 
- Video codec: h.264 
- Audio codec: aac 
- Frame rate: 25 FPS 
- Aspect ratio: 16:9 
- Resolution: 640 x 360 
- Video bit rate: 2 – 5 Mb/s 
- Audio bit rate: up to 256 kb/s 
- Audio channels: stereo 

Do run the the .ipynb files in Jupyter Notebook. 
