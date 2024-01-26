plugins {
    id("java")
}

group = "ru.netology"
version = "1.0-SNAPSHOT"

repositories {
    mavenCentral()
}

dependencies {
    testImplementation("io.rest-assured:rest-assured:5.3.2")
    testImplementation("org.junit.jupiter:junit-jupiter:5.10.0")
    implementation("io.rest-assured:json-schema-validator:5.3.2")
}

tasks.test {
    useJUnitPlatform()
}