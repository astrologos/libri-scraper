# libri-scraper
The Libri Scraper downloads full audiobook MP3's from LibriVox.org. It is meant to assist in building an labeled speech dataset for use in training neural Text-To-Speech systems in conjunction with Automatic Speech Recognition models.

## Requirements:

#### Mount Google Drive
To run this notebook, you need to mount your Google Drive. The notebook mounts your Google Drive and sets the current directory to the location of the notebook in your drive.

#### Install Chromium and Selenium
This notebook requires Chromium and Selenium to be installed. The code provided installs Chromium and its driver for running Selenium. It also installs the necessary Python library, Selenium, using pip.

## Data:
LibriVox provides free public-domain audiobooks read by volunteers from around the world.  It is not transcribed or diarized.  Future work will involve both transcription and diarization.  Once compiled, the dataset will be available on HuggingFace.

This code is licensed under the Creative Commons Attribution-NonCommercial (CC BY-NC) license, allowing for non-commercial use and modification with proper attribution. See the license here: https://creativecommons.org/licenses/by-nc/2.0/
