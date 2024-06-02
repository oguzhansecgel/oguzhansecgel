# 💫 About Me:
🌱 I’m currently learning Spring Boot, .Net Core

<div align="center"><img height="300" src="https://octodex.github.com/images/daftpunktocat-guy.gif" /></div>

# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)

# 📊 GitHub Stats:
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=oguzhansecgel&theme=dark&hide_border=false&include_all_commits=true&count_private=true"/><br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=oguzhansecgel&theme=dark&hide_border=false"/><br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oguzhansecgel&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact"/><br/>
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=oguzhansecgel&theme=nord&v=2&layout=compact&langs_count=10&hide=Markdown,Config,xml,yaml,json,Cocoa,Solution+file,Csproj,textmate,Gitignore+file,Other,Text,cshtml,Groovy,IL,AUTO_DETECTED,csharp,Jsonc,Publish+Profile+file" alt="oguzhansecgel's wakatime stats"/>
</div>

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=oguzhansecgel&limit=5&theme=dark&combine_all_yearly_contributions=true)

### 😂 Random Dev Meme
<img src='https://randommeme-five.vercel.app/' style="height: 400px;"/>

<!--START_SECTION:waka-->
## 📅 WakaTime Weekly Stats:

```

```

```

```
## 📅 WakaTime Weekly Stats:

```

```

```
Command line interface used by all WakaTime text editor plugins.

Usage:
  wakatime-cli [flags]

Flags:
      --alternate-branch string          Optional alternate branch name. Auto-detected branch takes priority.
      --alternate-language string        Optional alternate language name. Auto-detected language takes priority.
      --alternate-project string         Optional alternate project name. Auto-detected project takes priority.
      --api-url string                   API base url used when sending heartbeats and fetching code stats. Defaults to https://api.wakatime.com/api/v1/.
      --category string                  Category of this heartbeat activity. Can be "coding", "building", "indexing", "debugging", "learning", "meeting", "planning", "researching", "communicating", "running tests", "writing tests", "manual testing", "writing docs", "code reviewing", "browsing", "translating", or "designing". Defaults to "coding".
      --config string                    Optional config file. Defaults to '~/.wakatime.cfg'.
      --config-read string               Prints value for the given config key, then exits.
      --config-section string            Optional config section when reading or writing a config key. Defaults to [settings]. (default "settings")
      --config-write stringToString      Writes value to a config key, then exits. Expects two arguments, key and value. (default [])
      --cursorpos int                    Optional cursor position in the current file.
      --disable-offline                  Disables offline time logging instead of queuing logged time.
      --entity string                    Absolute path to file for the heartbeat. Can also be a url, domain or app when --entity-type is not file.
      --entity-type string               Entity type for this heartbeat. Can be "file", "domain" or "app". Defaults to "file".
      --exclude strings                  Filename patterns to exclude from logging. POSIX regex syntax. Can be used more than once.
      --exclude-unknown-project          When set, any activity where the project cannot be detected will be ignored.
      --extra-heartbeats                 Reads extra heartbeats from STDIN as a JSON array until EOF.
      --file-experts                     Prints the top developer within a team for the given entity, then exits.
      --guess-language                   Enable detecting language from file contents.
  -h, --help                             help for wakatime-cli
      --hide-branch-names string         Obfuscate branch names. Will not send revision control branch names to api.
      --hide-file-names string           Obfuscate filenames. Will not send file names to api.
      --hide-project-folder              When set, send the file's path relative to the project folder. For ex: /User/me/projects/bar/src/file.ts is sent as src/file.ts so the server never sees the full path. When the project folder cannot be detected, only the file name is sent. For ex: file.ts.
      --hide-project-names string        Obfuscate project names. When a project folder is detected instead of using the folder name as the project, a .wakatime-project file is created with a random project name.
      --hostname string                  Optional name of local machine. Defaults to local machine name read from system.
      --include strings                  Filename patterns to log. When used in combination with --exclude, files matching include will still be logged. POSIX regex syntax. Can be used more than once.
      --include-only-with-project-file   Disables tracking folders unless they contain a .wakatime-project file. Defaults to false.
      --internal-config string           Optional internal config file. Defaults to '~/.wakatime/wakatime-internal.cfg'.
      --is-unsaved-entity                Normally files that don't exist on disk are skipped and not tracked. When this option is present, the main heartbeat file will be tracked even if it doesn't exist. To set this flag on extra heartbeats, use the 'is_unsaved_entity' json key.
      --key string                       Your wakatime api key; uses api_key from ~/.wakatime.cfg by default.
      --language string                  Optional language name. If valid, takes priority over auto-detected language.
      --line-additions int               Optional number of lines added since last heartbeat in the current file.
      --line-deletions int               Optional number of lines deleted since last heartbeat in the current file.
      --lineno int                       Optional line number. This is the current line being edited.
      --lines-in-file int                Optional lines in the file. Normally, this is detected automatically but can be provided manually for performance, accuracy, or when using --local-file.
      --local-file string                Absolute path to local file for the heartbeat. When --entity is a remote file, this local file will be used for stats and just the value of --entity is sent with the heartbeat.
      --log-file string                  Optional log file. Defaults to '~/.wakatime/wakatime.log'.
      --log-to-stdout                    If enabled, logs will go to stdout. Will overwrite logfile configs.
      --metrics                          When set, collects metrics usage in '~/.wakatime/metrics' folder. Defaults to false.
      --no-ssl-verify                    Disables SSL certificate verification for HTTPS requests. By default, SSL certificates are verified.
      --offline-count                    Prints the number of heartbeats in the offline db, then exits.
      --output string                    Format output. Can be "text", "json" or "raw-json". Defaults to "text".
      --plugin string                    Optional text editor plugin name and version for User-Agent header.
      --print-offline-heartbeats int     Prints offline heartbeats to stdout. (default 10)
      --project string                   Override auto-detected project. Use --alternate-project to supply a fallback project if one can't be auto-detected.
      --project-folder string            Optional workspace path. Usually used when hiding the project folder, or when a project root folder can't be auto detected.
      --proxy string                     Optional proxy configuration. Supports HTTPS SOCKS and NTLM proxies. For example: 'https://user:pass@host:port' or 'socks5://user:pass@host:port' or 'domain\user:pass'
      --send-diagnostics-on-errors       When --verbose or debug enabled, also sends diagnostics on any error not just crashes.
      --ssl-certs-file string            Override the bundled CA certs file. By default, uses system ca certs.
      --sync-offline-activity int        Amount of offline activity to sync from your local ~/.wakatime.bdb bolt file to your WakaTime Dashboard before exiting. Can be zero or a positive integer. Defaults to 1000, meaning after sending a heartbeat while online, all queued offline heartbeats are sent to WakaTime API, up to a limit of 1000. Zero syncs all offline heartbeats. Can be used without --entity to only sync offline activity without generating new heartbeats. (default 1000)
      --time float                       Optional floating-point unix epoch timestamp. Uses current time by default.
      --timeout int                      Number of seconds to wait when sending heartbeats to api. Defaults to 120 seconds. (default 120)
      --today                            Prints dashboard time for today, then exits.
      --today-goal string                Prints time for the given goal id today, then exits Visit wakatime.com/api/v1/users/current/goals to find your goal id.
      --today-hide-categories string     When optionally included with --today, causes output to show total code time today without categories. Defaults to false.
      --verbose                          Turns on debug messages in log file, and sends diagnostics if a crash occurs.
      --version                          Prints the wakatime-cli version number, then exits.
      --write                            When set, tells api this heartbeat was triggered from writing to a file.
```
## 📅 WakaTime Weekly Stats:

```

```

```
Command line interface used by all WakaTime text editor plugins.

Usage:
  wakatime-cli [flags]

Flags:
      --alternate-branch string          Optional alternate branch name. Auto-detected branch takes priority.
      --alternate-language string        Optional alternate language name. Auto-detected language takes priority.
      --alternate-project string         Optional alternate project name. Auto-detected project takes priority.
      --api-url string                   API base url used when sending heartbeats and fetching code stats. Defaults to https://api.wakatime.com/api/v1/.
      --category string                  Category of this heartbeat activity. Can be "coding", "building", "indexing", "debugging", "learning", "meeting", "planning", "researching", "communicating", "running tests", "writing tests", "manual testing", "writing docs", "code reviewing", "browsing", "translating", or "designing". Defaults to "coding".
      --config string                    Optional config file. Defaults to '~/.wakatime.cfg'.
      --config-read string               Prints value for the given config key, then exits.
      --config-section string            Optional config section when reading or writing a config key. Defaults to [settings]. (default "settings")
      --config-write stringToString      Writes value to a config key, then exits. Expects two arguments, key and value. (default [])
      --cursorpos int                    Optional cursor position in the current file.
      --disable-offline                  Disables offline time logging instead of queuing logged time.
      --entity string                    Absolute path to file for the heartbeat. Can also be a url, domain or app when --entity-type is not file.
      --entity-type string               Entity type for this heartbeat. Can be "file", "domain" or "app". Defaults to "file".
      --exclude strings                  Filename patterns to exclude from logging. POSIX regex syntax. Can be used more than once.
      --exclude-unknown-project          When set, any activity where the project cannot be detected will be ignored.
      --extra-heartbeats                 Reads extra heartbeats from STDIN as a JSON array until EOF.
      --file-experts                     Prints the top developer within a team for the given entity, then exits.
      --guess-language                   Enable detecting language from file contents.
  -h, --help                             help for wakatime-cli
      --hide-branch-names string         Obfuscate branch names. Will not send revision control branch names to api.
      --hide-file-names string           Obfuscate filenames. Will not send file names to api.
      --hide-project-folder              When set, send the file's path relative to the project folder. For ex: /User/me/projects/bar/src/file.ts is sent as src/file.ts so the server never sees the full path. When the project folder cannot be detected, only the file name is sent. For ex: file.ts.
      --hide-project-names string        Obfuscate project names. When a project folder is detected instead of using the folder name as the project, a .wakatime-project file is created with a random project name.
      --hostname string                  Optional name of local machine. Defaults to local machine name read from system.
      --include strings                  Filename patterns to log. When used in combination with --exclude, files matching include will still be logged. POSIX regex syntax. Can be used more than once.
      --include-only-with-project-file   Disables tracking folders unless they contain a .wakatime-project file. Defaults to false.
      --internal-config string           Optional internal config file. Defaults to '~/.wakatime/wakatime-internal.cfg'.
      --is-unsaved-entity                Normally files that don't exist on disk are skipped and not tracked. When this option is present, the main heartbeat file will be tracked even if it doesn't exist. To set this flag on extra heartbeats, use the 'is_unsaved_entity' json key.
      --key string                       Your wakatime api key; uses api_key from ~/.wakatime.cfg by default.
      --language string                  Optional language name. If valid, takes priority over auto-detected language.
      --line-additions int               Optional number of lines added since last heartbeat in the current file.
      --line-deletions int               Optional number of lines deleted since last heartbeat in the current file.
      --lineno int                       Optional line number. This is the current line being edited.
      --lines-in-file int                Optional lines in the file. Normally, this is detected automatically but can be provided manually for performance, accuracy, or when using --local-file.
      --local-file string                Absolute path to local file for the heartbeat. When --entity is a remote file, this local file will be used for stats and just the value of --entity is sent with the heartbeat.
      --log-file string                  Optional log file. Defaults to '~/.wakatime/wakatime.log'.
      --log-to-stdout                    If enabled, logs will go to stdout. Will overwrite logfile configs.
      --metrics                          When set, collects metrics usage in '~/.wakatime/metrics' folder. Defaults to false.
      --no-ssl-verify                    Disables SSL certificate verification for HTTPS requests. By default, SSL certificates are verified.
      --offline-count                    Prints the number of heartbeats in the offline db, then exits.
      --output string                    Format output. Can be "text", "json" or "raw-json". Defaults to "text".
      --plugin string                    Optional text editor plugin name and version for User-Agent header.
      --print-offline-heartbeats int     Prints offline heartbeats to stdout. (default 10)
      --project string                   Override auto-detected project. Use --alternate-project to supply a fallback project if one can't be auto-detected.
      --project-folder string            Optional workspace path. Usually used when hiding the project folder, or when a project root folder can't be auto detected.
      --proxy string                     Optional proxy configuration. Supports HTTPS SOCKS and NTLM proxies. For example: 'https://user:pass@host:port' or 'socks5://user:pass@host:port' or 'domain\user:pass'
      --send-diagnostics-on-errors       When --verbose or debug enabled, also sends diagnostics on any error not just crashes.
      --ssl-certs-file string            Override the bundled CA certs file. By default, uses system ca certs.
      --sync-offline-activity int        Amount of offline activity to sync from your local ~/.wakatime.bdb bolt file to your WakaTime Dashboard before exiting. Can be zero or a positive integer. Defaults to 1000, meaning after sending a heartbeat while online, all queued offline heartbeats are sent to WakaTime API, up to a limit of 1000. Zero syncs all offline heartbeats. Can be used without --entity to only sync offline activity without generating new heartbeats. (default 1000)
      --time float                       Optional floating-point unix epoch timestamp. Uses current time by default.
      --timeout int                      Number of seconds to wait when sending heartbeats to api. Defaults to 120 seconds. (default 120)
      --today                            Prints dashboard time for today, then exits.
      --today-goal string                Prints time for the given goal id today, then exits Visit wakatime.com/api/v1/users/current/goals to find your goal id.
      --today-hide-categories string     When optionally included with --today, causes output to show total code time today without categories. Defaults to false.
      --verbose                          Turns on debug messages in log file, and sends diagnostics if a crash occurs.
      --version                          Prints the wakatime-cli version number, then exits.
      --write                            When set, tells api this heartbeat was triggered from writing to a file.
```
<!--END_SECTION:waka-->

---
[![](https://visitcount.itsvg.in/api?id=oguzhansecgel&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
