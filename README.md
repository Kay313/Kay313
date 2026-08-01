<div align="center">

<img src="https://raw.githubusercontent.com/Kay313/Kay313/main/assets/hero.svg" alt="Kay313 — Backend &amp; Infrastructure Engineer" width="100%">

<br>

[![Website](https://img.shields.io/badge/megabuild.de-22153A?style=for-the-badge&logo=googlechrome&logoColor=C985FF)](https://megabuild.de)
[![Discord](https://img.shields.io/badge/Discord-22153A?style=for-the-badge&logo=discord&logoColor=C985FF)](https://megabuild.de/dc)
[![Shop](https://img.shields.io/badge/Shop-22153A?style=for-the-badge&logo=shopify&logoColor=C985FF)](https://shop.megabuild.de)
[![Wiki](https://img.shields.io/badge/Wiki-22153A?style=for-the-badge&logo=readthedocs&logoColor=C985FF)](https://wiki.megabuild.de)
[![Status](https://img.shields.io/badge/Status-22153A?style=for-the-badge&logo=statuspage&logoColor=8CFFB8)](https://status.megabuild.de)

<!-- Optional: E-Mail-Badge. Bewusst auskommentiert — eine öffentlich sichtbare
     Adresse auf dem GitHub-Profil zieht erfahrungsgemäß Spam an. Einfach die
     nächste Zeile entkommentieren, wenn du das trotzdem möchtest.
[![Mail](https://img.shields.io/badge/Mail-22153A?style=for-the-badge&logo=gmail&logoColor=FF91E9)](mailto:kay.fehr31@gmail.com)
-->

<img src="https://raw.githubusercontent.com/Kay313/Kay313/main/assets/divider.svg" alt="" width="100%">

</div>

<details open>
<summary><b>&nbsp;🇩🇪&nbsp; Deutsch</b></summary>

<br>

### Moin, ich bin Kay 👋

Ich baue die technische Infrastruktur hinter **[MegaBuild.de](https://megabuild.de)** — einem deutschen Minecraft-Netzwerk. Vom Proxy über die SkyBlock-Server bis zu Shop, Wiki und Management-Panel läuft das meiste auf Code, den ich selbst schreibe.

Mein Schwerpunkt sind **Java-Backends und verteilte Server-Systeme**: Velocity-Proxies, CloudNet-Cluster, MariaDB — also alles, was dafür sorgt, dass Spieler sauber zwischen Servern wechseln, ohne dass unterwegs etwas verloren geht. Das Frontend drumherum mache ich dann auch gleich mit.

**Woran ich gerade sitze**

- **Sichere Rejoin-Logik für SkyBlock-Inseln** — CloudNet vergibt Service-IDs nach einem Stop neu, der Proxy muss also prüfen, ob jemand wirklich auf seine *eigene* Insel zurückkommt
- **Bedrock-Parität über Geyser** — eigene Biome und Resourcepacks, die auf Java und Bedrock identisch aussehen
- **CloudNet Panel** — ein Web-Panel für CloudNet, ungefähr in der Liga von Pterodactyl

### Projekte

| Projekt | Worum es geht | Stack |
| :--- | :--- | :--- |
| **MBPM** | Proxy-Kern des Netzwerks: Chat, Commands, Vanish, Onlinetime, Resourcepacks, sichere SkyBlock-Rejoins | Java · Velocity · MariaDB · HikariCP |
| **MBSkyManager** | Das SkyBlock-System — Insel-Verwaltung, eigene Biome, Bedrock-Support über Geyser | Java · Paper · Geyser |
| **MBSkyConnector** | Bindeglied zwischen Proxy und den einzelnen SkyBlock-Instanzen | Java · CloudNet |
| **CloudNet Panel** | Web-Panel für CloudNet: Server steuern, Live-Konsole, Backups, granulare Rechte | React · Tailwind · Node · WebSocket · JWT |
| **MagicCloset** | Digitaler Kleiderschrank mit KI-Outfit-Assistent und virtueller Anprobe | Expo · React Native · TypeScript · SQLite · Ollama |
| **MBSimple** | Fabric-Mod, die den WorldEdit-Schematic-Workflow für Builder automatisiert | Java · Fabric · WorldEdit |

**Außerdem:** `MBF3` (Client-Mod mit eigenem Debug-Overlay via Mixins) · `LobbyMiniCore` (Lobby, NPCs, Spawn) · `MBAIO` (Votestreaks, Plots) · `MBManager` (Freundesystem, Timed Messages) · `Drachus`, `MBMod`, `MBBeats` (Discord-Bots, Musik über LavaPlayer) · `MBVoidWorld` (Void-Weltgenerator) · Website und Shop auf megabuild.de

</details>

<details>
<summary><b>&nbsp;🇬🇧&nbsp; English</b></summary>

<br>

### Hey, I'm Kay 👋

I build the infrastructure behind **[MegaBuild.de](https://megabuild.de)**, a German Minecraft network. From the proxy through the SkyBlock servers to the shop, wiki and management panel — most of it runs on code I write myself.

My focus is **Java backends and distributed server systems**: Velocity proxies, CloudNet clusters, MariaDB — everything that keeps players moving cleanly between servers without losing state on the way. I build the frontend around it too.

**What I'm working on right now**

- **Safe rejoin logic for SkyBlock islands** — CloudNet recycles service IDs after a stop, so the proxy has to verify that someone is actually returning to *their own* island
- **Bedrock parity through Geyser** — custom biomes and resource packs that look identical on Java and Bedrock
- **CloudNet Panel** — a web panel for CloudNet, roughly in Pterodactyl's league

### Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **MBPM** | The network's proxy core: chat, commands, vanish, playtime, resource packs, safe SkyBlock rejoins | Java · Velocity · MariaDB · HikariCP |
| **MBSkyManager** | The SkyBlock system — island management, custom biomes, Bedrock support via Geyser | Java · Paper · Geyser |
| **MBSkyConnector** | The link between the proxy and the individual SkyBlock instances | Java · CloudNet |
| **CloudNet Panel** | Web panel for CloudNet: server controls, live console, backups, granular permissions | React · Tailwind · Node · WebSocket · JWT |
| **MagicCloset** | Digital wardrobe with an AI outfit assistant and virtual try-on | Expo · React Native · TypeScript · SQLite · Ollama |
| **MBSimple** | Fabric mod that automates the WorldEdit schematic workflow for builders | Java · Fabric · WorldEdit |

**Also:** `MBF3` (client mod with a custom debug overlay via Mixins) · `LobbyMiniCore` (lobby, NPCs, spawn) · `MBAIO` (vote streaks, plots) · `MBManager` (friends system, timed messages) · `Drachus`, `MBMod`, `MBBeats` (Discord bots, music via LavaPlayer) · `MBVoidWorld` (void world generator) · the website and shop on megabuild.de

</details>

<div align="center">

<img src="https://raw.githubusercontent.com/Kay313/Kay313/main/assets/divider.svg" alt="" width="100%">

### Stack

**Backend**

![Java](https://img.shields.io/badge/Java-22153A?style=for-the-badge&logo=openjdk&logoColor=C985FF)
![Maven](https://img.shields.io/badge/Maven-22153A?style=for-the-badge&logo=apachemaven&logoColor=C985FF)
![Gradle](https://img.shields.io/badge/Gradle-22153A?style=for-the-badge&logo=gradle&logoColor=C985FF)
![MariaDB](https://img.shields.io/badge/MariaDB-22153A?style=for-the-badge&logo=mariadb&logoColor=C985FF)
![Velocity](https://img.shields.io/badge/Velocity-22153A?style=for-the-badge)
![Paper](https://img.shields.io/badge/Paper-22153A?style=for-the-badge)
![CloudNet](https://img.shields.io/badge/CloudNet-22153A?style=for-the-badge)
![Fabric](https://img.shields.io/badge/Fabric-22153A?style=for-the-badge)

**Frontend &amp; Apps**

![TypeScript](https://img.shields.io/badge/TypeScript-22153A?style=for-the-badge&logo=typescript&logoColor=C985FF)
![Expo](https://img.shields.io/badge/Expo-22153A?style=for-the-badge&logo=expo&logoColor=C985FF)
![Tailwind](https://img.shields.io/badge/Tailwind-22153A?style=for-the-badge&logo=tailwindcss&logoColor=C985FF)
![Node.js](https://img.shields.io/badge/Node.js-22153A?style=for-the-badge&logo=nodedotjs&logoColor=C985FF)
![Laravel](https://img.shields.io/badge/Laravel-22153A?style=for-the-badge&logo=laravel&logoColor=C985FF)

**Infrastruktur &amp; Tools**

![Linux](https://img.shields.io/badge/Linux-22153A?style=for-the-badge&logo=linux&logoColor=C985FF)
![Nginx](https://img.shields.io/badge/Nginx-22153A?style=for-the-badge&logo=nginx&logoColor=C985FF)
![Git](https://img.shields.io/badge/Git-22153A?style=for-the-badge&logo=git&logoColor=C985FF)
![Python](https://img.shields.io/badge/Python-22153A?style=for-the-badge&logo=python&logoColor=C985FF)
![IntelliJ](https://img.shields.io/badge/IntelliJ-22153A?style=for-the-badge&logo=intellijidea&logoColor=C985FF)

<img src="https://raw.githubusercontent.com/Kay313/Kay313/main/assets/divider.svg" alt="" width="100%">

<!-- Die folgenden Karten kommen von Drittanbieter-Diensten (github-readme-stats,
     demolab). Sie sind in den MegaBuild-Farben eingefärbt, können aber gelegentlich
     langsam laden oder ausfallen — dann sind sie kurz als kaputtes Bild zu sehen.
     Wenn dich das stört: Block einfach löschen, der Rest der Seite bleibt intakt. -->

<img src="https://github-readme-stats.vercel.app/api?username=Kay313&show_icons=true&rank_icon=github&border_radius=14&bg_color=170D29&title_color=C985FF&icon_color=FF91E9&text_color=DDD2EE&border_color=422B6C" alt="GitHub Stats" height="170">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kay313&layout=compact&langs_count=8&border_radius=14&bg_color=170D29&title_color=C985FF&text_color=DDD2EE&border_color=422B6C" alt="Top Languages" height="170">

<br><br>

<img src="https://streak-stats.demolab.com/?user=Kay313&border_radius=14&background=170D29&border=422B6C&stroke=422B6C&ring=C985FF&fire=FF91E9&currStreakLabel=C985FF&sideLabels=DDD2EE&dates=AB9DC0&currStreakNum=FFFAFF&sideNums=FFFAFF" alt="Streak" height="170">

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Kay313&radius=14&bg_color=170D29&color=DDD2EE&title_color=C985FF&line=C985FF&point=FF91E9&area=true&area_color=A958FF&border_color=422B6C" alt="Activity Graph" width="100%">

<br><br>

<img src="https://raw.githubusercontent.com/Kay313/Kay313/main/assets/footer.svg" alt="Danke fürs Vorbeischauen — Thanks for stopping by" width="100%">

</div>
