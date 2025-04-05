<h1 align="center">😎 Customize  
    <a href="https://github.com/bia-pain-bache/BPB-Worker-Panel">BPB Panel 💦</a> 
</h1>

[**English**](https://liMilCo.github.io/BPB-ReCoder/README_en)   -   [فارسی](https://liMilCo.github.io/BPB-ReCoder)

---

😎 Using this Online APP:
<p align="left">
  <a href="https://liMilCo.github.io/BPB-ReCoder/recoder.html">https://liMilCo.github.io/BPB-ReCoder/recoder.html</a>
  <br>
  or
  <br>
  <a href="https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html">https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html</a>
</p>

<p align="justify">
You can customize the BPB Panel.
</p>

## First Step

<a href="https://liMilCo.github.io/BPB-ReCoder/recoder.html" target="_blank">Access the online tool here...</a>

### Paste original BPB project codes in the first box:

<img src="doc/1.png" width="100%">

<h3>Get Project Codes: 
    <a href="https://github.com/bia-pain-bache/BPB-Worker-Panel/releases" target="_blank">BPB Panel</a>
</h3>


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

## Project View
![Counter](https://count.getloli.com/@BPB-ReCoder?name=BPB-ReCoder&theme=sketch-1&padding=5)

## Stargazers over time
[![Stargazers over time](https://starchart.cc/liMilCo/BPB-ReCoder.svg?variant=adaptive)](https://starchart.cc/liMilCo/BPB-ReCoder)

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
