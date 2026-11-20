# murakumo.sh

The install address for [Murakumo](https://murakumo.ai):

```bash
curl -fsSL https://murakumo.sh | sh
```

This repository holds no script of its own. Its workflow copies the installer that
[murakumo.ai/install.sh](https://murakumo.ai/install.sh) serves, which comes from
[website/home/install.sh](https://github.com/murakumo-data/murakumo/blob/main/website/home/install.sh)
in the main repository and is tested there on clean Ubuntu and macOS runners before it is
published. It republishes here when that file changes (checked every hour, or run the workflow by
hand).

What murakumo.sh serves:

| Address | What it is |
| --- | --- |
| `https://murakumo.sh` | The installer. A browser that opens it is sent to the install docs |
| `https://murakumo.sh/install.sh` | The same installer, as it is |

Change the installer in the main repository, not here.
