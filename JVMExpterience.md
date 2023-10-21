# Исследование JVM через VisualVM

*11:33:00.906874: loading io.vertx\
*11:33:01.405116100: loaded 529 classes\
11:33:04.421586800: loading io.netty\
11:33:05.229130: loaded 2117 classes\
11:33:08.242402300: loading org.springframework\
11:33:08.573185400: loaded 869 classes\
11:33:11.573848700: now see heap\
11:33:11.573848700: creating 5000000 objects\
11:33:12.047124500: created\
11:33:15.059353900: creating 5000000 objects\
11:33:15.374123200: created\
11:33:18.446309500: creating 5000000 objects\
11:33:18.774518300: created\


Происходит загрузка библиотек (их классов) в метаспейс\
io.vertx\
io.netty\
org.springframework\


далее создаются объекты в куче\
11:33:11 5000000 - объектов\
11:33:15 ещё 5000000 - объектов\
11:33:18 ещё 5000000 - объектов\

## Classes

![classes](https://github.com/TatarinovAn/JVMExpt/blob/main/Classes.PNG?raw=true) 


## Heap

![heap](https://github.com/TatarinovAn/JVMExpt/blob/main/Heap.PNG?raw=true)


## Metaspace

![metaspace] (https://github.com/TatarinovAn/JVMExpt/blob/main/Metaspace.PNG?raw=true)