<h1 align="center">😎 Customize  
    <a href="https://github.com/bia-pain-bache/BPB-Worker-Panel">BPB Panel 💦</a> 
</h1>
<h2 align="center">Solving Error 1011</h2>

😎 Using [this project](https://github.com/liMilCo/BPB-ReCoder): https://liMilCo.github.io/BPB-ReCoder  
<p align="left">
  <a href="https://liMilCo.github.io/BPB-ReCoder/recoder.html">https://liMilCo.github.io/BPB-ReCoder/recoder.html</a>
  <br>
  or
  <br>
  <a href="https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html">https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html</a>
</p>

<p align="justify">
You can fully customize the panel codes. Since Cloudflare reviews and bans projects by detecting codes, to avoid Error 1011 you must change keywords like function names, panel access URLs, variable data, and KV database identifiers. While some projects have done this, their new codes may eventually get detected. The best solution is for each user to create a panel with personalized codes, which this tool helps you achieve.
</p>

## First Step

<a href="https://liMilCo.github.io/BPB-ReCoder/recoder.html" target="_blank">Access the online tool here...</a>

### Paste original BPB project codes in the first box:

<img src="doc/1.png" width="100%">

<h3>Get Project Codes: 
    <a href="https://github.com/bia-pain-bache/BPB-Worker-Panel" target="_blank">BPB-Worker-Panel</a>
</h3>
<p align="center">
    <strong>
<a href="https://github.com/bia-pain-bache/BPB-Worker-Panel/releases/download/v2.7.4/worker.js" target="_blank">BPB 2.7.4</a>
 - 
<a href="https://raw.githubusercontent.com/liMilCo/BPB-ReCoder/main/worker.2.8.1.js" target="_blank">BPB 2.8.1</a>
 - 
<a href="https://github.com/bia-pain-bache/BPB-Worker-Panel/releases/download/v3/unobfuscated-worker.js" target="_blank">BPB 3.0.0</a>
    </strong>
</p>

## Second Step

### Enter Panel Login Credentials (Mandatory 😱)

📝 Use only lowercase English letters

**Open fields are mandatory. Closed fields like (Main Page) or (Sub Functions) can be left empty**

<img src="doc/2.png" width="100%">

Note: When deploying your customized project on GitHub, replace `panel` in the URL:
<br>
`BPB.SUB.workers.dev/panel`  
with your chosen word (e.g., if you select `myadmin`, access via):
<br>
`BPB.SUB.workers.dev/myadmin`

### Select a Website for Root Page (Optional 😴)
Default is Cloudflare's Speedtest. Leave empty to keep default.
If entering a custom URL:
- Ensure correct spelling
- Choose lightweight sites to avoid overloading Cloudflare

<img src="doc/3.png" width="100%">

### Enter KV Database & Cloudflare Variables (Mandatory 😱)

After creating KV storage, you must rename it from default `bpb`.

📝 KV Name: lowercase English only

Also change these variables used in `Settings` > `Variables and Secrets`:
- UUID
- TROJAN_PASS  
- PROXYIP  

📝 Variable names: English letters (case-sensitive)

<img src="doc/4.png" width="100%">

Example:

<img src="doc/5.png" width="100%">

### Note: Case sensitivity matters! Store these names securely.

**👈 These names save in browser cache after first run, but better to write them down 👉**

### Rename Core Functions (Mandatory 😱)
Original function names like `vlessOverWSHandler` and `handleTCPOutBound` are easily detected.

📝 English words only (min 5 chars)

Click 🎁 to generate random names.

<img src="doc/6.png" width="100%">

### Advanced Function Renaming (Optional 😴)

Sub-functions can also be renamed for extra security (not mandatory).

📝 English words only (min 5 chars)

<img src="doc/7.png" width="100%">

## Third Step

Click `Generate New BPB 🌊` to apply changes.  
Modified codes will appear in the box - ready to download.

<img src="doc/8.png" width="100%">

## Fourth Step  
Use `Obfuscator Code 💨` to obfuscate generated code.  
Copy-paste directly into Workers or download for Pages deployment (zip first).

<img src="doc/9.png" width="100%">

<details>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-THQL9EQWDS"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-THQL9EQWDS');
</script>
<style> html {direction: ltr;} </style>
</details>
