# Console Radio

Requirement: Python (2 or 3).

To start download just run:

    python ./download.py -c activity__sex -n 5
    python ./download.py -c user__270453501 -s "3:1472313987.5.0.1472313963000:YS5VXQ:41.0|270453501.24.2.2:24|150707.721938.Y0a_8wRdhS1stARnY1ABTqFZfrk0"

Play:

    service mpd start

Run web UI:

    sudo ./ympd --webport 80 &

Upload to Google Drive:

    ./gdrive sync upload $RADIO_DIR_LOCAL $RADIO_DIR_GDRIVE
