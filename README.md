# Conv1D_ecological

The features extracted with VGGish are hosted at https://drive.google.com/file/d/1aHMGSk3mNhAHHnPS1Q9-oSZjAyRzFtvz/

If you want to download the extracted features with VGGish:

`!wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=1aHMGSk3mNhAHHnPS1Q9-oSZjAyRzFtvz' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=1aHMGSk3mNhAHHnPS1Q9-oSZjAyRzFtvz" -O VGGFeat.zip && rm -rf /tmp/cookies.txt`

Then you must unzip the downloaded zip file:

`!unzip "path_to_file/VGGFeat.zip" -d "path_to_file/VGGfeatures/"`
