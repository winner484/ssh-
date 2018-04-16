# ssh-
ssh迁移后工作
# 1 sudo apt-get install ssh
# 2 ssh username@192.168.0.3
# 3 将文件价从远程拷贝到本机  
    scp -r localfile.txt username@192.168.0.3:/home/fengyu/
    
# 4 本机 到 远程
    scp -r /home/feng/robot fengyu@192.168.0.3:/home/fengyu/pyproject/
    
# 5 修改配置文件，然后运行。import cv2    cv2.__version__
