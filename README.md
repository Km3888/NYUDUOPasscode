<h1> Chinese </h1> 

###new feature
自动复制到剪贴板


##全平台DUO passcode开源获取程序 python ver

听说anyconnect也要MFA了那就先写个自动获取passcode的组件x

和移动端DUO push说再见）

简单说明（过两天写详细说明）
首次使用:
1. 系统命令行运行 pip install pyotp， pip install pyperclip（或者cd进本文件所在的文件夹然后pip install -r requirements.txt）
2. 在start.nyu.edu注册一个新的android平板设备,在扫描QR code那一步右键二维码选择复制图片链接，
3. 然后在secret.conf里把链接粘贴进去（注意保留引号）
4. 然后运行init.py


之后每次想要passcode的话运行passcode.py就会自动写进clipboard一个passcode啦

可以把这几个文件藏起来然后建个passcode.py的shortcut

然后把这个passcode贴进2nd password的地方


###搞不来首次使用的配置可以请kris上门服务（？


<h1>English Translation</h1>

###new feature:Automatically copy to clipboard


##Cross-platform DUO passcode acquisition script


Instructions:
1. First run pip install pyotp， pip install pyperclip（or navigate to the base directory and run pip install -r requirements.txt）
2.  Go to start.nyu.edu and under the 'additional settings' option register a new android tablet device. When given the QR code for registration, copy this link to the clipboard，
3. Then open the secret.conf and paste the url
4. Finally, run init.py

Afterwards whenever you want an MFA passcode, you can just run passcode.py and a passcode will be copied to your clipboard.

To make it more convenient, these files can be easily accessed through a shortcut.

The password copied to the clipboard can then be pasted into the 2nd password field.

********All credit to the original author********
