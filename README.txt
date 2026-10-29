1) unzip smart-iptv.zip && cd smart-iptv
2) git init && git add . && git commit -m init && git branch -M main
3) git remote add origin https://github.com/zarzouramahmoudabdo-commits/smart-iptv.git && git push -u origin main
4) Actions -> Build APK -> Artifacts. Enable Pages from gh-pages branch (for the in-app update button).
To ship an update without new APK: raise VER in www/index.html, push.
