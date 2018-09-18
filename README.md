
# CVE-2018-8420  
## xzbgs&Chaitin tech
修改了原POC `xml.xml` 中的一个单引号问题。  
增加了一个IE远程利用方式。

vbs本地点开即可弹出计算器.  
html文件IE远程命令执行.

问题的根源在于msxml解析器的问题，所以估计还有很多程序、功能都有调用了这个组件，也存在相应的问题，后续有时间补充。
![演示](https://github.com/Lz1y/CVE-2018-8420/blob/master/9%E6%9C%88-12-2018%2020-18-25.gif?raw=true)
## Affected Products  
Windows 7 for 32-bit Systems Service Pack 1  
Windows 7 for x64-based Systems Service Pack 1  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core installation)  
Windows Server 2008 R2 for Itanium-Based Systems Service Pack 1  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core installation)  
Windows Server 2012  
Windows Server 2012 (Server Core installation)  
Windows 8.1 for 32-bit systems  
Windows 8.1 for x64-based systems  
Windows Server 2012 R2  
Windows RT 8.1  
Windows Server 2012 R2 (Server Core installation)  
Windows 10 for 32-bit Systems  
Windows 10 for x64-based Systems  
Windows Server 2016  
Windows 10 Version 1607 for 32-bit Systems  
Windows 10 Version 1607 for x64-based Systems  
Windows Server 2016 (Server Core installation)  
Windows 10 Version 1703 for 32-bit Systems  
Windows 10 Version 1703 for x64-based Systems  
Windows 10 Version 1709 for 32-bit Systems  
Windows 10 Version 1709 for x64-based Systems  
Windows Server, version 1709 (Server Core Installation)  
Windows 10 Version 1803 for 32-bit Systems  
Windows 10 Version 1803 for x64-based Systems  
Windows Server, version 1803 (Server Core Installation)  
Windows Server 2008 for Itanium-Based Systems Service Pack 2  
Windows Server 2008 for 32-bit Systems Service Pack 2  
Windows Server 2008 for x64-based Systems Service Pack 2  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core installation)  
