<!-- Org profile README · rendered at https://github.com/SecureCMD -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:04111f,55:061a33,100:0b2545&height=220&section=header&text=Secure%20Code%20MetaDynamics&fontColor=f2a93b&fontSize=42&fontAlignY=38&desc=security%20by%20design%20%E2%80%A2%20built%20in%20the%20open&descSize=16&descAlignY=58&animation=fadeIn" alt="Secure Code MetaDynamics" width="100%" />

<a href="https://securecmd.com">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=20&pause=1200&color=F2A93B&center=true&vCenter=true&width=640&lines=%24+sudo+make+it+secure;%24+git+commit+-m+%22no+more+plaintext+passwords%22;%24+echo+%22security+can+be+friendly%22;%24+curl+-I+https%3A%2F%2Fsecurecmd.com+%23+200+OK" alt="sudo make it secure" />
</a>

<br/>

[![Website](https://img.shields.io/badge/securecmd.com-061a33?style=for-the-badge&logo=firefoxbrowser&logoColor=f2a93b)](https://securecmd.com)
[![Blog](https://img.shields.io/badge/blog-061a33?style=for-the-badge&logo=rss&logoColor=f2a93b)](https://securecmd.com/blog/index.html)
[![X](https://img.shields.io/badge/@SecureCMD-061a33?style=for-the-badge&logo=x&logoColor=f2a93b)](https://x.com/SecureCMD)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-061a33?style=for-the-badge&logo=linkedin&logoColor=f2a93b)](https://www.linkedin.com/company/secure-code-metadynamics)
[![PGP](https://img.shields.io/badge/PGP-C144%2098D2-f2a93b?style=for-the-badge&logo=gnuprivacyguard&logoColor=1a1203&labelColor=061a33)](https://securecmd.com/pgp-key.asc)

</div>

```text
   ███████╗ ██████╗███╗   ███╗██████╗
   ██╔════╝██╔════╝████╗ ████║██╔══██╗
   ███████╗██║     ██╔████╔██║██║  ██║   Secure Code MetaDynamics
   ╚════██║██║     ██║╚██╔╝██║██║  ██║   ~ small team, big on details ~
   ███████║╚██████╗██║ ╚═╝ ██║██████╔╝   loc: Spain, EU
   ╚══════╝ ╚═════╝╚═╝     ╚═╝╚═════╝    lang: en | es | it | pt
```

## `~/hello`

We're **SecureCMD**, a small software company from Spain that builds, hardens and looks after
software that really can't afford to break. Our day job is serious stuff — but we're developers
first, and we like to share the tools we write along the way.

Our favourite idea: **security shouldn't feel like a punishment.** Good defaults, readable code
and boring deploys make everybody's life easier (and we love boring deploys).

```diff
+ secure defaults, out of the box
+ code you can read, review and trust
+ signed builds & SBOMs, because "it works on my machine" isn't a supply chain
+ docs written by humans, for humans
- security theatre
- "we'll add auth later"
- passwords in plaintext. ever.
```

## `~/projects`

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/SecureCMD/tmux-opener"><code>tmux-opener</code></a></h3>
      <p>Your tmux sessions, one click away. A tiny native macOS app that opens local or SSH tmux sessions in iTerm.</p>
      <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
      <img src="https://img.shields.io/badge/macOS-14%2B-061a33?style=flat-square&logo=apple&logoColor=white" alt="macOS 14+" />
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/SecureCMD/cobiserver"><code>cobiserver</code></a></h3>
      <p>Self-hosted KOReader sync server. Drop-in compatible, with a self-service account UI. Your reading progress, on your own box.</p>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/self--hosted-f2a93b?style=flat-square&logoColor=1a1203" alt="self-hosted" />
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/SecureCMD/libmitmpy"><code>libmitmpy</code></a></h3>
      <p>A Python playground for man-in-the-middle experiments. <em>“But won't somebody please think of the children's security?!”</em></p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/research-061a33?style=flat-square" alt="research" />
    </td>
  </tr>
</table>

> [!TIP]
> Found something useful? A star makes our day. Found a bug? An issue makes our code better. Both are welcome!

## `~/workflow`

```mermaid
flowchart LR
    A["your idea"] --> B["build<br/>secure by design"]
    B --> C["harden<br/>audit & shrink the attack surface"]
    C --> D["respond<br/>we stay on call"]
    D -. "learn, improve, repeat" .-> B
    D --> E["everybody sleeps well"]

    classDef night fill:#061a33,stroke:#2d5482,color:#dce6f2
    classDef amber fill:#f2a93b,stroke:#f2a93b,color:#1a1203
    class A,B,C,D night
    class E amber
```

We lean on open standards instead of reinventing them: **OWASP ASVS**, **NIST SSDF**,
**ISO/IEC 27001**, **ENS**, **NIS2** and **DORA**.

## `~/contact`

<details>
<summary><code>$ report --vuln</code> &nbsp;Found a security issue in one of our repos?</summary>
<br/>

Thanks for looking out for us! Please **don't open a public issue** — check our
[`security.txt`](https://securecmd.com/.well-known/security.txt) and send us an encrypted note with our
[PGP key](https://securecmd.com/pgp-key.asc):

```text
C240 53A5 A5F7 200C 4772  DDE5 8EBD B4BC C144 98D2
```

We'll get back to you quickly, keep you in the loop, and credit you if you'd like.

</details>

<details>
<summary><code>$ ping securecmd</code> &nbsp;Want to work with us, or just say hi?</summary>
<br/>

Drop by [securecmd.com](https://securecmd.com), read the [blog](https://securecmd.com/blog/index.html),
or ping us on [X](https://x.com/SecureCMD). PRs, ideas and memes are all accepted
(the memes go through code review too).

</details>

<div align="center">

<br/>

<sub><code>// made with coffee, git rebase -i and a healthy amount of paranoia in Spain</code></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b2545,45:061a33,100:04111f&height=110&section=footer" alt="" width="100%" />

</div>
