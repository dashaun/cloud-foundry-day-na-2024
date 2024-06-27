### 3. Dependency Management

- Apps need to bring their dependencies with them
- Containers
- Maven, Gradle, NuGet, Bundler, Godeps, PyPi
- "Release Train"

Notes:
- Apps bring everything with them
- Feature code, runtime, OS
- Least privilege principle
- your code cannot rely on the pre-existence of dependencies on a deployment target
- Zero assumptions

---

### What is on the menu?
<br>

```text
spring project-catalog list

spring project list
```
> Supported. Reference implementations.

---

### Demo

```text
spring boot new cfday web
```