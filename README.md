download the version from secure link

https://drive.proton.me/urls/9X3P0CHB90#gqEZJboWKhkZ

you need to install Termux and then run the following commands to use the app to its full abilities

termux-setup-storage                 # Allow termux to download files into your phone's storage
pkg update && pkg upgrade            # Update all packages
pkg install libexpat openssl python  # Install python
pip install -U "yt-dlp[default]"     # Install yt-dlp with default dependencies
pkg install ffmpeg                   # OPTIONAL: Install ffmpeg
