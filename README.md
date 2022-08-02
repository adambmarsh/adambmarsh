## Hi, I am Adam 👋 

I’m a software engineer and technical writer who is passionate about making processes and tools easier to understand through automation and better documentation.

📫 How to reach me:
- LinkedIn: [Adam Bukolt](https://www.linkedin.com/in/adam-bukolt-8216981/)
- [ORT Slack channel](https://join.slack.com/t/ort-talk/shared_invite/zt-1c7yi4sj6-mk7R1fAa6ZdW5MQ6DfAVRg): Thomas Steenbergen

💬 Ask me anything living in Southern Ireland, Python or about my growing number of Linux machines  💻

🏳️‍🌈 Pronouns: he/him

### Projects I'm busy with...

#### [OSS Review Toolkit](https://github.com/oss-review-toolkit/ort)

OSS Review Toolkit (ORT) provides tooling to safely use, integrate, modify and redistribute third party software including [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software). 

You can use it to:
- Generate [CycloneDX](https://cyclonedx.org) or [SPDX](https://spdx.dev) SBOMs for your software project
- Automate your FOSS policy using _Policy as Code_ to do licensing, security vulnerabilities and engineering standards checks for your software project and its dependencies
- Correct found invalid or missing package metadata (licensing, source location, etc.)
- Overwrite scanner license findings in the sources of your software project and its dependencies
- Mark files, directories or or package manager scopes as not included in your software project or dependency released artifacts - use it to make clear that license findings in build scripts, documentation or tests in a package sources do not apply to the release (binary) artifact
- Create a source code archive for your software project, including its dependencies to comply with certain licenses or have your own copy as nothing on the internet is forever

I regularly contribute to the ORT documentation to help its users better understand how they can use tool to review their software projects

#### [music_base](https://github.com/adambmarsh/music_base)

I plan this as an on-going experiment, with a possibility to open-source any
generic solutions the project may offer. The current incarnation harvests music
metadata from music and yaml files and writes it to a PostgreSQL database. 

The goal is to provide a search facility. The idea stems from the limitations and
lack of portability and flexibility in the available solutions:

- I can play music locally, using VLC, but searchability is limited
- If I play music on my NAS, search facilities are extremely poor to
  non-existent, so I am reduced to browsing through a directory structure of
  1200+ albums/CDs and 16000+ songs; if I can't think of a name or title, I have
  to go to my computer to find it (ultimately using find + grep, etc.)

The project thus far has offered good scope for experimenting with:
  - Django's ORM
  - asynchronous processing (coroutines)
  
Planned enhancements:

- create a Web GUI with a search box and an area to display the search results:
  - search to be text- and regex-based

- build a playlist from the query results
- play the playlist on a music player -- either local or a network resource

