# unraid-templates

unRAID Community Applications templates by svantetobias.

| App | Template | Image |
|---|---|---|
| Connectome (unofficial; [upstream](https://github.com/anima-research/connectome-host)) | [connectome.xml](connectome.xml) | [ghcr.io/svantetobias/connectome](https://github.com/svantetobias/connectome-docker) |

## Install without CA

In unRAID: **Docker → Add Container → Template**, or save the raw XML to
`/boot/config/plugins/dockerMan/templates-user/my-connectome.xml` and choose it under *Add Container*:

```
https://raw.githubusercontent.com/svantetobias/unraid-templates/main/connectome.xml
```

Connectome is an unofficial community packaging. The upstream project has no license and isn't affiliated with this repo.
