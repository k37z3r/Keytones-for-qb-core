# Keytones-for-qb-core
© Copyright 2022 all rights reserved<br>
<br>
All contents, especially the source code of all files, are protected by copyright. All rights, including reproduction, publication, editing and translation, are reserved.<br>
<br>
<br>
If your QB-Phone doesn't play key tones, this package will help you.<br>
<br>
<br>
Installation:<br>
<br>
1. Move the folder `audio` to: `./resource/[qb]/[phone]/html/`
2. Move the file `keytone.js` to: `./resource/[qb]/[phone]/html/js/`
3. Open the file: `./resource/[qb]/qb-phone/html/index.html`
4. Search in the file for: `<script src="./js/camera.js"></script>`
5. After that, paste: `<script src="./js/keytone.js"></script>`
6. Save and close
7. Open the file: `./resource/[qb]/qb-phone/fxmanifest.lua`
8. Search in the file for: `files {`
9. After that, paste: `'html/audio/*.mp3',`
10. Save and close
<br>
restart script (better restart server), DONE!<br>
<br>
required:<br>
qb-phone
