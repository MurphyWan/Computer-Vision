# Computer-Vision

# 在Window环境中安装OpenCV3
## 用最笨的办法在win7 64位中Python2.7环境下安装OpenCV3

### 0下载若干文件:
  
  #### 1)	python2.7 64位
  #### 2)	OpenCV3.1.0
  #### 3)	下载numpy+mkl 64位（http://www.lfd.uci.edu/~gohLke/pythonlibs/#numpy），文件名：numpy-1.11.3+mkl-cp27-cp27m-win_amd64.whl
  #### 4)	下载scipy 64位（http://www.lfd.uci.edu/~gohLke/pythonlibs/#scipy），文件名：scipy-0.18.1-cp27-cp27m-win_amd64.whl

### 1安装.whl文件方法：
  
  #### 1).先安装PIP（Python27自带）
  #### 2).CMD命令进入C:\Python27\Scripts里面，后再执行PIP命令安装pip install wheel
  #### 3).把文件(numpy、scipy)最好放在\Scripts文件夹里面，再pip install xxxx.whl 
  #### 4).注意whl文件名不能改 必须一模一样和原名

### 2.将build\pthon\x64\cv2.pyd拷贝到C:\Python27\Lib\site-packages目录下

### 3.测试是否可用，可用则ok
