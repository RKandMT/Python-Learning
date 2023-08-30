# 安装方式
```
pip install ansys-mapdl-core
```
# 查看自己的电脑是否可以使用pyansys
```
>>>from ansys.mapdl.core import launch_mapdl
>>>mapdl = launch_mapdl()
>>>print(mapdl)
```
显示以下内容即可：
```
Product:             ANSYS Mechanical Enterprise
MAPDL Version:       21.1
ansys.mapdl Version: 0.65.2
```
