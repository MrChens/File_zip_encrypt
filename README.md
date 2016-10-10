#What is this?
将文件打包并计算打包后文件的MD5值，并使用3Des加密该MD5值，并通过webServers来实现下载这个打包好的zip文件。
Download the ziped file which contains other file and the key file,the content of the key file is calculate the script.zip MD5 value and using tripleDes to encrypt it。
#webServers usage:
1. run webServers with following command：       
    ./webServers
2. the download url is :http://127.0.0.1:8880/
---

#filePacker.php usage:
1. before run filePacker you should change the value of `cryptKey` and `iv`.

2. run filePacker.php with the following command(source_file1 and source_file2 are the files that you want package):        
        php filePacker.php source_file1 source_file2
