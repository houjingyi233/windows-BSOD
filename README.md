# windows-BSOD

found 2 BSOD on latest win10 by using [RPC-forge](https://github.com/sogeti-esec-lab/RPCForge).The first one also exists on latest win10
insider preview.

They cannot be further exploited,as far as I know.MSRC refused to fix them because"The ability to crash the machine you already have logged onto and have the ability to run malicious programs would not meet the bar".

To reproduse them install https://github.com/hakril/PythonForWindows and run "python poc.py" or just run packed poc.exe.Then you should see something like:

![image](https://github.com/houjingyi233/Screenshots/blob/master/BSOD.PNG)  
