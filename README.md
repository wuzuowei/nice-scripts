# Collection of useful scripts
主要收集一些自己觉得好用的脚本/项目


## weblogic

### CVE-2020-14882
- https://github.com/NS-Sp4ce/CVE-2020-14882/blob/main/14882.py


## spring

### Spring Boot Actuator未授权访问
- https://github.com/rabbitmask/SB-Actuator


## redis

### redis未授权访问
- https://github.com/n0b0dyCN/redis-rogue-server
- https://github.com/vulhub/redis-rogue-getshell（前者修改版）


## 尝试找出cdn背后的真实ip

- https://github.com/3xp10it/xcdn

## SvnExploit(支持SVN源代码泄露全版本Dump源码)

- https://github.com/admintony/svnExploit

## Spring Boot Vulnerability Exploit Check List
  Spring Boot 相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估 check list
  - https://github.com/LandGrey/SpringBootVulExploit#0x03eureka-xstream-deserialization-rce


  一：信息泄露
  二：远程代码执行
  
    0x01：whitelabel error page SpEL RCE
    
    0x02：spring cloud SnakeYAML RCE
    
    0x03：eureka xstream deserialization RCE
    
    0x04：jolokia logback JNDI RCE
    
    0x05：jolokia Realm JNDI RCE
    
    0x06：restart h2 database query RCE
    
    0x07：h2 database console JNDI RCE
    
    0x08：mysql jdbc deserialization RCE
    
    0x09：restart logging.config logback JNDI RCE
    
    0x0A：restart logging.config groovy RCE
    
    0x0B：restart spring.main.sources groovy RCE
    
    0x0C：restart spring.datasource.data h2 database RCE
    
