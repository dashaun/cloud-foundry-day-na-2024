### 4. Design, Build, Release and Run

---

#### Design

- Design small features

```bash
spring project list

spring boot add restdocs 
```

Notes:
- I made a point to make several commits along the way already
- Easier to test, easier to rollback or roll-forward

---

#### Build

- Convert code into a versioned binary artifact
- Jar, tgz, Docker Image

```bash
./mvnw clean package
```

Notes:
- The automation that I'm running could easily be converted to a pipeline
- CI doesn't need to be overly complex to be effective

---

#### Release

- Unique
- Identifiable
- Auditable

```bash
git add .
git commit -m "cfday"
git tag v0.0.1
```

Notes:
- Who made the changes
- What version was running at a given time
- What changes were made from the previous version

---

#### Run

- Developer Ability to run locally
- Multiple Cloud Platforms
- Platform provides "abilities"
<br>
<br>
```bash
./mvnw spring-boot:run
```

Notes:
- Being 15factor focused helps the big picture
- Fault tolerance
- Scalability
- Monitoring health
