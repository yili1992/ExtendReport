# 简介
基于ExtendReport 实现 Suite->Test->Class->TestMethod 层次关系的报告。
报告中 包含tearDown setUp等 configurationTest 信息。并且Step的统计不会记录configurationTest。

![image](https://github.com/yili1992/ExtendReport/raw/master/asset/1.jpg)

#如何使用
testng.xml 中增加listener


    <listeners>
          <listener class-name="com.XXX.XXX.ExtentTestNGIReporterListener"></listener>
    </listeners>
>基于开源项目中ExtendReport开发：
[api_autotest](https://github.com/ChenSen5/api_autotest/blob/master/src/main/java/com/sen/api/listeners/ExtentTestNGIReporterListener.java)

