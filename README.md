# spring-boot-jsp
spring boot整合jsp

 * 返回jsp的demo，需要注意:
 * 1.打包是war,不是jar，否则还是404,启动脚本在demo目录Start.bat
 * 2.注意配置前缀后缀后，注意webapp的目录，是和java同一级别
 * 3.注意POM中 有2个依赖的<scope>provided</scope>需要注释掉，否则会找不到servlet等.....Eclipse不用注释
