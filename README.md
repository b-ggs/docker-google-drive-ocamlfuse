# docker-google-drive-ocamlfuse

dockerized [google-drive-ocamlfuse](https://github.com/astrada/google-drive-ocamlfuse)

## Usage

* Run the container with:

```
docker run -d --rm -v $(pwd):/mnt/gdrive -p 5901:5901 bxggs/google-drive-ocamlfuse
```

* Access the container through VNC (password is **vncpassword**)

* Sign in to Google Drive on Firefox when prompted, and authorize the app

* After the app has been authorized, your Google Drive folder should be mounted on `/mnt/gdrive` and should be available on your bindmounted directory

