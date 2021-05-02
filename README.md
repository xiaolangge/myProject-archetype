### usage of archetype-template

    1.将写好的archetype-xxx安装到本地仓库: mvn clean install
    2.使用模板创建项目: 

    mvn archetype:generate  -B \
    -DarchetypeGroupId=org.example \
    -DarchetypeArtifactId=myProject-archetype \
    -DarchetypeVersion=1.0-SNAPSHOT \
    -DgroupId=org.example2 \
    -DartifactId=demo \
    -Dversion=1.1-SNAPSHOT \
    -Dpackage=org.example \
    -Dport=6379


