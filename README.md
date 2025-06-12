mvn tomcat7:run
task run(type: JavaExec) {
main = 'com.example.App'
classpath = sourceSets.main.runtimeClasspath
}

plugins {
id 'java'
}
