## In terminal:
sudo apt-get install -y python-numpy cmake zlib1g-dev libjpeg-dev libboost-all-dev gcc libsdl2-dev wget unzip

## In forder mujoco_py:
sudo pip3 install -e . --no-cache

## In hw1
sudo pip3 install openai gym tensorflow

## In .mujoco/ add key.txt and mujoco unzip

## Export path to ~/.bashrc
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/(name_user)/.mujoco/mjpro150/bin
