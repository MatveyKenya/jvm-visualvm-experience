# Изучение использования памяти через VisualVM
### при загрузке новых классов и создании новых объектов

![metaSpace](https://user-images.githubusercontent.com/67868199/128621150-cd4ee3cd-6feb-4bae-8037-e4037bc20d88.png)

1.--- 08:43:29.181960500: loading io.vertx --- начало загрузки классов в Metaspace из пакета io.vertx

2.--- 08:43:29.460023300: loaded 529 classes --- классы io.vertx загруженыв  Metaspace

3.--- 08:43:32.469768300: loading io.netty --- начало загрузки классов в Metaspace из пакета io.netty

4.--- 08:43:33.027895300: loaded 2117 classes --- классы io.netty загружены в Metaspace

5.--- 08:43:36.032487: loading org.springframework --- начало загрузки классов в Metaspace из пакета org.springframework

6.--- 08:43:36.251539200: loaded 869 classes --- классы org.springframework загружены в Metaspace

08:43:39.257139: now see heap --- дело дошло до кучи

![heap](https://user-images.githubusercontent.com/67868199/128621182-3f978c82-429b-4f08-ace7-15b166ed14da.png)

7---- 08:43:39.257139: creating 5000000 objects --- начало создания 5_000_000 объектов в куче

8---- 08:43:39.522200100: created ---- 5_000_000 объектов создано в куче

9---- 08:43:42.536461800: creating 5000000 objects--- начало создания 5_000_000 объектов в куче

10--- 08:43:42.726503400: created --- 5_000_000 объектов создано в куче

11--- 08:43:45.833321500: creating 5000000 objects --- начало создания 5_000_000 объектов в куче

12--- 08:43:46.035367700: created --- 5_000_000 объектов создано в куче
