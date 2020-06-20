# Cut_and_convert_audio
For this script to work, you need to download ffmpeg from the official site and register the full path to exe file in path_to_ffmpeg
# Instruction:
1. in variable length_of_chunk you must indicate the number of seconds of one chopped chunk
2. in variable count_chunks you must indicate the number of chunks
3. run the program using the command line (cmd) 
# program call example:
C:\>python C:\Cut_and_convert_audio\cut_audio.py C:\data_set

Where:

the first parameter - is the path to the python interpreter

the second parameter - is the path to the .py file

the third parameter - is the path to the folder with your .wav files
# note1: 
file checking happens recursively, that is, all .wav attached files starting from the specified path
# note2: 
do not pay attention to the warning: "RuntimeWarning: Couldn't find ffmpeg or avconv - defaulting to ffmpeg, but may not work
  warn("Couldn't find ffmpeg or avconv - defaulting to ffmpeg, but may not work", RuntimeWarning)"
