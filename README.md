#audio recording using linux
sudo apt install ffmpeg -y ( install ffmpeg command to record audio)
sudo apt update            ( update the installed ffpmeg files)
sudo apt upgrade           ( update the installed ffpmeg files)
pulseaudio --start         (to intialize the soundcards)
ffmpeg -f pulse -i default -t 60 output.wav  (command line to record audio in terminal )


#python script to play recorded mp3 file
pip install --upgrade setuotools wheel  (to install and upgrade the pip extension in python)
pip install playsound                    (using playsound we play the mp3 file)

code:-
{
from playsound import playsound
playsound("C:\\Users\\aqib0\\aqib.wav")
}
