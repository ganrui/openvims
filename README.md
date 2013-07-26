openvims
========
open vim scripts

use step:

1.    git clone https://github.com/ganrui/openvims.git

2.    cd .vim

3.    git submodule init

4.    git submodule update

5. if your vim is gvim for windows, please change the name ".vim" to "vimfiles"

6. Warning:This step will override your ".vimrc" file by openvim's ".vimrc" 

    execute the "Install.sh" 

7. if you want to add other vim-scripts, you can do it yourself like this:

    git submodule add https://github.com/scrooloose/nerdcommenter.git bundle/nerdcommenter

8. To push yourself vim scripts --"vimfiles" directories to github.com, do like this:
    
8.1 create git repository on github.com

    goto url:   https://github.com/ganrui/openvims.git

    Fork it to youself github count's repo

8.2 git clone youself openvims' repo to your PC.

8.3 do some changes what you want to do to the ".vim" files.

8.4 then

        git commit 

        git push


