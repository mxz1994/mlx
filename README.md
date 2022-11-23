# mlx

## 1. 项目启动准备

flutter create mlx

修改配置文件
android\gradle\gradle-wrapper.properties   

修改build.gradle  

        google()
        mavenCentral()

        替换为

        maven { url 'https://maven.aliyun.com/repository/google' }
        maven { url 'https://maven.aliyun.com/repository/jcenter' }
        maven { url 'http://maven.aliyun.com/nexus/content/groups/public' }