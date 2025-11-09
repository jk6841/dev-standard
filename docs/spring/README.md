# Spring

## 프로젝트 설정
### [spring initializer](https://start.spring.io)

- project: `Gradle - Kotlin`
- language: `Kotlin`
- packaging: `jar`
- configuration: `YAML`

## check list
### Containerfile
- base image version

### build.gradle.kts
- task `jar` 비활성화
```kotlin
tasks {
    jar {
        enabled = false
    }
}
```