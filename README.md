# Sample From Youtube
The purpose of this script is to make it easier to obtain musical samples from YouTube.

## Installation:
Clone repository

```git clone https://github.com/qkcire/sample_from_youtube.git```

Install dependencies

```brew install ffmpeg```

```brew install youtube-dl```

## Instructions:
Copy and paste the youtube ID of the sample (everything after the 'https://www.youtube.com/watch?v=') and give it a name

```./sample_from_youtube [YOUTUBE_ID] [NAME_OF_FILE]```

```./sample_from_youtube ybfQRvl5r-I how_to_say_sample```


After some time, the script should output a file of the sample in .wav format to your ```SAMPLES_STORAGE_PATH``` directory.