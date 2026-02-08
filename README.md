# datascraping_2025-2026
This repo contains code to retrieve podcasts from an RSS-Feed. It saves the .mp3 audio files onto your mass storage device and is also able to collect some metadata if available. </br>
Retrieving podcast audio files is a bit boring in itself so this repo also contains code for some ML (the buzzword of our times). </br>
Audio files are transcribed to text using `faster-whisper` by Klein et al. (see their Github [here](https://github.com/SYSTRAN/faster-whisper). `faster-whisper` is a reimplementation of the original `whisper` by OpenAI (see [here](https://github.com/openai/whisper). </br>
Performance and accuracy are measured.
