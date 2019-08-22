### dagger2
---
https://github.com/google/dagger

https://google.github.io/dagger/

```java
http_archive(
  name = "com_google_dagger",
  urls = ["https://github.com/google/dagger/archive/dagger-<version>.zip"]
)

gradle.projectsEvaluated {
  tasks.withType(JavaCompile) {
    options.compilerArgs << "-Xmaxerrs" << "500"
  }
}
```

```
```

```
```


