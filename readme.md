1.spark在windows上local模式下的缺失winutils.exe异常  
下载**相应版本**文件粘贴到相应文件夹

2.Exception in thread “main” org.apache.spark.SparkException: A master URL must be set in your configuration  
在右侧VM options中输入“-Dspark.master=local”，指示本程序本地单线程运行，再次运行即可。