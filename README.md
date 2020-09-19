# Windows-bugs-solution
This repository is for solutions of Windows bugs based on using experience.

### 1、Get Administrator's permition of windows for installing the special modules
### solution: (1) #: runas /noprofile /user:Administrator cmd;(2)input the key.
if you forget the key, you can reset the key by: #: net user administrator <your new key\>

## Refuse Slow download of anaconda
## solution: 

(1)input following 4 commands:

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/

conda config --set show_channel_urls yes

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/

(2)copy command for Govern page with no '-c';
over
