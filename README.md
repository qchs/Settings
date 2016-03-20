# Settings
All the links and description of install packages that need to use.

1.Chrome

  search in baidu.https://www.baidu.com/   %>_<%
  
  
2.Verify the hosts.

  http://laod.cn/hosts
  
  After this ,Chrome's app store is able to open.
  
  (Try Currently:http://www.cnplugins.com/news/currently/ 
  
  or Momentum：http://www.cnplugins.com/office/momentum/download.html)
  
  
3.See a bigger world.

  https://link.zhihu.com/?target=https%3A//raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-beta.exe
  
  
4.python

  https://www.python.org/
  
  
5.pyCharm 

  http://www.jetbrains.com/pycharm/
  
  Community is enough.Run local web file must turn off VPN.
  
  
6.Install package for pyCharm.

 a.First,make sure pip is installed well,in cmd,input pip -version
 
 b.Then install in pyCharm:File->Default Settings-> search project interpreter
 
 c.Another solution: in cmd, pip3 install packagename 
 
 
7.install lxml for pyCharm

 Download lxml:http://www.lfd.uci.edu/~gohlke/pythonlibs/#lxml
 
 in cmd :
 pip3 install wheel,
 
 then cd c:\path, 
 
 finally pip3 install **.whl
 
 
 
 8.MongoDB
 
  https://www.mongodb.org/downloads#production
  
  Don't install in c:, can't start .bat
  
  After install,go into the file ,create a file (let's say data),
  
  then use a .bat to start MongoDB,in .bat store :
  
  mongod --dbpath./data
  
  With .bat is on ,use MongoVue to see this database.
  
  install MongoVue need .NET framework, win10 has it,but need to start it by chosen.
  
  
  
  
 9.MongoVue(do not support python 3)
 
  http://www.mongovue.com/downloads/
  
  While use MongoVue,.bat must stay open. So the connection will hold.
  
  
 10.pyCharm mongo plugin 
 
 Show the mongoDB dirrectly in the IDE.
 
