# Spring

## 프로젝트 설정
### [spring initializer](https://start.spring.io)

- project: `Gradle - Kotlin`
- language: `Kotlin`
- packaging: `jar`
- configuration: `YAML`

## check list
### [공통](../README.md#check-list)
### build.gradle.kts
- task `jar` 비활성화
```kotlin
tasks {
    jar {
        enabled = false
    }
}
```