## TODO
- [ ] FIgure out version for server & modpack
- [ ] Server properties e.g. more resources
- [ ] Automate download of modpack

## General
|           |            |
| --------  | -------    |
| JAVA      | 17         |
| MOD       | ATM9       |
| MC VERSION| 1.20.1     |

## Test locally
Change `CF_API_KEY` within `docker-compose.yml` to own CurseForge API key

    $ docker compose up -d

### Connecting to server
1. Install [Prism](https://prismlauncher.org/wiki/getting-started/installing-prismlauncher/) launcher
2. Install **Java 17** (through [Adoptium](https://adoptium.net/temurin/releases/?version=17&os=windows))
3. Open up Prism and select Adoptium's Java 17 with an upper limit of `8192MB` of memory
4. Link with Microsoft account
5. Click on "Add instance" -> "CurseForge" and search for **All the Mods 9 - ATM9**
6. Start up instance and connect directly to `localhost:25565`

## References
[itzg / docker-minecraft-server](https://github.com/itzg/docker-minecraft-server?tab=readme-ov-file)
