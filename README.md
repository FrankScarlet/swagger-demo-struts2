# Struts2 & Swagger

## 变动

1. struts2升级到了最新的`2.5.26`版本
2. 通过jetty运行，插件版本用的`9.4.29.v20200521`
3. swagger4j升级到了`2.2.1`（以及它的依赖库）

## 进展

- [x] 纯文字API解析OK http://localhost:8080/api/ 
- [ ] 在`web.xml`中加入`/doc/*`无效

## 最好能完成

- [ ] 在Struts`2.5.26`下用上`Swagger`，有稳定的可视化的接口文档（快了）
- [ ] 在上个条件下，下钻到JDK1.7的支持（最好能实现）
- [ ] `Struts1`的支持（issue区里也看到有人提这个，但感觉太难完成了）

