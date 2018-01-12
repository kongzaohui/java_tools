# java_tools

https://www.tutorialspoint.com/java_xml/java_dom_parse_document.htm

https://stackoverflow.com/questions/1537207/how-to-convert-xml-to-java-util-map-and-vice-versa

javabean的使用：可以使用set()方法往javabean中添加已经定义的字段



http://www.cnblogs.com/IamThat/p/3264234.html

http://www.cnblogs.com/fengmingyue/p/6048225.html

java.util.Date和java.sql.Date的区别及应用

Email-noLogin<br>
有一些server不需要login可以直接发送email，连接的时候采用<br>
props.setProperty("mail.smtp.auth", "false"); // 不需要请求认证<br>
Session session = Session.getInstance(props);<br><br>
//transport.connect(myEmailAccount, myEmailPassword);<br>
transport.connect();


#关于命名的技巧
使用时间作为命名的尾部，当做随机变量，不可控制，保证每次循环都不一样；<br>
使用可控变量作为头部，在for循环中，可以控制，保证每次循环都一样；<br>
巧妙地使用“_”作为连接字符，连接可控和不可控，在字符操作中也比较方便识别。

Write To Excel<br>
http://www.codejava.net/coding/how-to-write-excel-files-in-java-using-apache-poi
