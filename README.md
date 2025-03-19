# linux-check-filesize



```

#!/bin/sh

find /경로/logs/ -mtime +30 -delete    # 30일 지난 로그파일 삭제
find /경로/logs/ -size +1G -delete    # 사이즈가 1기가 넘은 파일 삭제
find /경로/log/nginx/ -mtime +30 -delete  # 30일 지난 로그파일 삭제


```
