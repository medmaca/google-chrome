# google-chrome
To keep Google Chrome linux versions for Dockerfiles.  Given that Google only retains Chrome versions for a brief period I want to store the ones I use so that in the future I can still build Docker images with the same package versions.

# chrome-versions
Commands used to pull distributions:

- `wget https://dl.google.com/linux/chrome/deb/pool/main/g/google-chrome-stable/google-chrome-stable_131.0.6778.85-1_amd64.deb`
- `wget https://dl.google.com/linux/chrome/deb/pool/main/g/google-chrome-stable/google-chrome-stable_132.0.6834.83-1_amd64.deb`

Note that version **131.0.6778.85-1** works using old `--headless` mode so can be used in Docker/Apptainer containers that use save_kable(table, out_name) & webshot2 to output to pdfs.