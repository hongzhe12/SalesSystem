# SalesSystem
自定义导入商品信息，生成销售数据，统计盈利情况。

#主程序名称:sale_system

1.用户通过扫描二维码的方式，程序读取商品名称和条码等信息，用户手动输入价格和销售地址后，程序自动记录信息生成一系列的信息至excel

2.用户通过使用 “录入商品条码”程序，程序将商品条码写入json文件中，在"sale_system"程序中选择下单的时候则在本地json文件中查找商品信息。

3."录入商品条码"程序使用了百度API扫描识别

4."sale_system"程序 使用excel在本地作为数据库,实现增删查改四项功能。


