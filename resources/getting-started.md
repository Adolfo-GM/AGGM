# Getting started with AGGM

1 - Download this repository by running the following command in your terminal:

```
git clone https://github.com/Adolfo-GM/AGGM
cd AGGM
```

2 - Download the AggmGPT-2 model by running the following command in your terminal:

```
git lfs install
git clone https://huggingface.co/Adolfo-GM/AggmGPT-2 temp-folder
mv temp-folder/* .
mv temp-folder/.* .  
rmdir temp-folder

```

3 - You can run ``` aggm.py ``` to see the demo.

4 - To run your own AGGM code, you can run:

 ``` 
 python aggmtopy.py main.aggm

 ``` 
 with main.aggm replaced by your file name.
- Note that this overview may not cover everything, you may need to do some tweaking to make the code work for your machine. 
