# m3
myo mini muscle
![m3](https://github.com/Roboy/m3/blob/master/images/m3.png?raw=true "m3")
![m3_schematics](https://github.com/Roboy/m3/blob/master/images/m3_schematics.png?raw=true "m3_schematics")

1. Download this repo using:
>> git clone --recursive https://github.com/Roboy/m3.git

2. Add the eps-idf and eps-idf/tools to your PATH:
>> export PATH=$PATH:~/workspace/m3/esp/esp-idf:~/workspace/m3/esp/esp-idf/tools

3. Set IDF_PATH to eps-idf:
>> export IDF_PATH=~/workspace/m3/esp/esp-idf

4. To build m3_control change into its directory and use idf to build
>> cd /esp/m3_control
>> idf.py build

5. Flash it. Hold down Reset and Boot.
>> idf.py -p [PORT] flash [monitor]

Let Reset go, while keeping Boot pressed until flashing is done.
