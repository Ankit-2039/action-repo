# action-repo

This repository is the source repository for the GitHub webhook assessment task. Any Push, Pull Request, or Merge action on this repo sends a webhook event to [webhook-repo](https://github.com/Ankit-2039/webhook-repo) for processing and display.

---

## Webhook Configuration

| Setting | Value |
|---|---|
| Payload URL | `https://cyndi-snecked-darkly.ngrok-free.dev/webhook/receiver` |
| Content type | `application/json` |
| Events | Pushes, Pull requests |

---

## How to trigger each event

| Event | How |
|---|---|
| **PUSH** | Push a commit to any branch |
| **PULL REQUEST** | Open a pull request between two branches |
| **MERGE** | Merge an open pull request |

---

## Viewing the activity feed

Open the UI at:

```
https://cyndi-snecked-darkly.ngrok-free.dev/
```

It polls for new events every 15 seconds automatically.

---
