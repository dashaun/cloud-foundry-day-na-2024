### 8. Backing Services

```text
A backing service is any service
on which your application relies
for its functionality.
```

Notes:
- data stores
- messaging systems
- caching systems
- security
- Line of business services
- Security

---

```bash
cf push loki --no-route --docker-image grafana/loki
```

---

```text
In the cloud
There is no filesystem
```

Notes:
- I need to get this on a t-shirt
- This is usually the first and last hurdle I see for teams moving towards 15-Factors

---

```text
An application should declare
its need for a given backing service
but allow the cloud environment
to perform the actual resource binding.
```

---

```text
The binding of an application
to its backing services
should be done via
external configuration.
```

---

```text
It should be possible to attach
and detach backing services
from an application at will,
without re-deploying the application.
```