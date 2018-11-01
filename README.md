## docker maven:3.5.4-jdk-8-alpine
https://github.com/carlossg/docker-maven/tree/f581ea002e5d067deb6213c00a4d217297cad469/jdk-8-alpine
#### Add setting.xml
```
  <mirrors>
    <mirror>
      <id>alimaven</id>
      <mirrorOf>central</mirrorOf>
      <name>aliyun maven</name>
      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
    </mirror>
  </mirrors>
```
