clone the official monome teletype repo  
fetch the tags with `git fetch --tags`  
checkout the v5.0.0 tag `git checkout v5.0.0`

clone this repo  
copy the `.diff` to your clone of the official repo  
check nothing's gone wrong with `git apply --check --verbose --ignore-whitespace --ignore-space-change more-scripts.diff`  
apply the patch - `git apply --verbose --ignore-whitespace --ignore-space-change more-scripts.diff`  

build the firmware as normal with the docker image, and follow the update procedure as normal.  
hooray, now you have more scripts! If this worked...
