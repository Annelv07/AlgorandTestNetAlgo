# Fill MyAlgo Wallet with TestNet test ALGOs

Algorand – the world’s most decentralised, scalable, secure and sustainable blockchain 
infrastructure founded by Silvio Micali in 2017.
<br><br>
Algorand is a next-generation layer-1 blockchain platform, featuring ALGO as its native 
token. It has many powerful features allowing it to solve the blockchain trilemma, and 
can support a wide range of important use cases, making it an attractive blockchain 
technology for any developer to learn. 
<br>
<br>
You can fill up your MyAlgo Wallet with a test ALGO easily through the link bellow <br>
https://bank.testnet.algorand.network/
<br>
<b>Make sure that you already created a MyAlgo Wallet because you will need to put in your wallet address</b><br>
You will be able to see your ALGO in <b> TestNet</b>, NOT IN <b>MainNet</b><br>
Aside from checking the amount from the wallet itself, you are able to check the amount available on your wallet through Python Code.


## Pre-requisite to check wallet amount through Python
Before executing the code, make sure that you've installed Algorand Python SDK. 
You can perform it by executing the command bellow in Windows Powershell or Zsh:
```
pip install py-algorand-sdk
```
or
```
pip3 install py-algorand-sdk
```

You can check details of py-algorand-sdk on the <a href="https://github.com/algorand/py-algorand-sdk">Official Github of Algorand</a>! <br>
See py-algorand-sdk documentation <a href="https://py-algorand-sdk.readthedocs.io/en/latest/index.html">here</a>!

#### Additional Notes
Before you run the code for to check the amount in wallet(not the SDK installation), make sure that you already set up Algorand Sandbox on your Linux, Windows Subsystem for Linux (Ubuntu), or Zsh environment. 

### Incase of Error
If there is an error showing that you are missing an import:
```
"X" could not be resolved Pylance(reportMissingImports)"
```
Then make sure you have changed the paths of your working Python environment to match 
the path where the Algorand Python SDK is installed. For example in <b>Spyder</b>, you can add a new PATH leads to the installed Algorand Python SDK through PythonPath Manager.

![image](https://user-images.githubusercontent.com/92056286/171984939-92b5234a-5349-4d7c-825a-fbdada040d75.png)

This can be accessed through ![image](https://user-images.githubusercontent.com/92056286/171984970-27a3ec90-9790-428f-a6e1-2b73f3814a4e.png)
icon or through 'Tools' > 'PYTHONPATH Manager'.

<br>
You can check the path of your installed Algorand Python SDK when you finished installed the package
or just re-run the installation command again (it won't be re-installed, instead it will show you
that it has been installed on the system)
