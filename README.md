# YouTube Video Uploader (Python 3)

This code is based on the example code on Google's documentation at:

https://developers.google.com/youtube/v3/guides/uploading_a_video

When I tried to make that `upload_video.py` work (early August 2024), I found that it written for Python 2. Further, it used some Python 2 techniques and referenced older libraries.

This code is a conversion that now runs on Python 3 with a requirements.txt file that brings in the right libraries.

```
$ python upload_video.py --help
usage: upload_video.py [--auth_host_name AUTH_HOST_NAME]
                       [--noauth_local_webserver]
                       [--auth_host_port [AUTH_HOST_PORT ...]]
                       [--logging_level {DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                       --file FILE [--title TITLE] [--description DESCRIPTION]
                       [--category CATEGORY] [--keywords KEYWORDS]
                       [--privacyStatus {public,private,unlisted}]
upload_video.py: error: the following arguments are required: --file
```

## Caveats

This project is probably not enough to get started, as you must follow steps (per code comments) to create a Google project (on [their console](https://console.cloud.google.com)), and then configure OAuth 2.0. Follow the links and read the code comments for learning those important steps.

## Author

Rick (rickumali@gmail.com) Umali
