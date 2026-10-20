<h1 align="center">Hey, I'm ricodev</h1>

<p align="center">
  Dev from Mexico. I write a lot of Java for Minecraft servers and a lot of TypeScript for everything else.
</p>

<p align="center">
  <a href="https://github.com/ricodevvv?tab=followers"><img src="https://img.shields.io/github/followers/ricodevvv?style=for-the-badge&logo=github&label=Followers&color=181717" /></a>
  <a href="https://discord.com/users/_vzqq"><img src="https://img.shields.io/badge/Discord-_vzqq-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=ricodevvv&label=Profile%20Views&style=for-the-badge&color=0e75b6" />
</p>

---

Most of my time goes into Minecraft infrastructure: minigame frameworks, server forks, packet NPCs, replays, matchmaking. Stuff that has to hold up with a full server and still run on 1.8.8. The other half is AI tooling. I self-host my own chat app, keep a fork of OpenCode, and build little tools around coding agents.

When I end up writing the same code in three plugins, it turns into a library. Those live on my own Maven repo at [maven.ricodevvv.com](https://maven.ricodevvv.com).

## Minecraft

| Project | What it is |
| --- | --- |
| [Riven](https://github.com/ricodevvv/Riven) | Minigame framework for Spigot 1.8.8. Arenas, teams, guided map setup, stats, cosmetics, parties and a Redis network layer, split into modules so you only pull what you use. |
| [Effigy](https://github.com/ricodevvv/Efiggy) | Packet NPCs with holograms, from 1.8.8 up to 26.3. The server never ticks them and other plugins never see them. |
| [Aurora](https://github.com/ricodevvv/Aurora) | Particles, animations, holograms and cosmetics from 1.8 to 1.21+ in one jar. Every particle draws *something* on every version. |
| [Quartz](https://github.com/ricodevvv/Quartz) | Commands, menus and scoreboards for Bukkit with zero dependencies. Annotate a method and that's your command, tab completion included. |
| [Codinject](https://github.com/ricodevvv/Codinject) | Downloads Maven dependencies at runtime, transitive ones too, with relocation. Java 8 to 25. Keeps plugin jars small. |
| [RankedQueue](https://github.com/ricodevvv/RankedQueue) | Ranked 2v2 queue for BedWars doubles. Rating-balanced teams, and the spread tolerance grows the longer you wait. |

## AI and agents

| Project | What it is |
| --- | --- |
| [Nexo](https://github.com/ricodevvv/NexoIA) | Self-hosted AI chat, kind of like claude.ai but with any provider. MCP, artifacts, projects, teams, a code sandbox and a coding agent that runs in containers on k3s. |
| [nexocode](https://github.com/ricodevvv/nexocode) | My fork of OpenCode. It's the agent behind Nexo Code and a couple of other things I run. |
| [Zordon](https://github.com/ricodevvv/zordon) | Run a bunch of coding agents in parallel, each in its own git worktree and branch, all on one screen. Single Go binary. |
| [agent-from-scratch](https://github.com/ricodevvv/agent-from-scratch) | A coding agent built in 10 small steps, ~200 lines of Python, no frameworks. Each step comes with a chapter explaining it. |

## Tools

| Project | What it is |
| --- | --- |
| [flaretun](https://github.com/ricodevvv/flaretun) | `npx flaretun 3000 --hostname dev.example.com` and your local server is on your domain through Cloudflare Tunnel. Same URL every time. |
| [stowage](https://github.com/ricodevvv/stowage) | One storage API for S3, R2, MinIO, local disk and memory. Swap the driver, keep the code. |
| [Reel](https://github.com/ricodevvv/Reel) | Self-hosted download panel. Paste a link and yt-dlp grabs it inside a throwaway container while the log streams to your browser. |

## Not public (yet)

A few bigger things are still private:

- **GodEyes**, Hypixel-style replays for 1.8.8, watched back from any angle, stored on S3.
- **UltraBedwars**, multi-arena BedWars with every mode, the Dream modes, private games and Hypixel-style prestiges.
- **GhostSpigot** and **Eclipse**, server forks. One is a 1.8.8 PvP fork with custom knockback, the other a Purpur fork for 26.3 that keeps big servers at 20 TPS.
- **Universe Client**, a Lunar-style launcher (Tauri + React) plus a Fabric mod with the HUD and cosmetics.
- **Linus**, an agent that lives in GitHub Actions, fixes labeled issues and opens the PR. It never deploys anything on its own.

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=java,kotlin,ts,go,py,rust" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,tauri,gradle,maven" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,docker,kubernetes,cloudflare,linux" />
</p>

<p align="center">
  <img src="contributions.svg" alt="Contribution graph" />
</p>
