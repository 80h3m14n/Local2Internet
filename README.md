<h1 align="center">Local2Internet</h1>

<p align="center">
   <img src="https://img.shields.io/badge/Author-KasRoudra-magenta?style=flat-square">
   <img src="https://img.shields.io/badge/Open%20Source-Yes-orange?style=flat-square">
   <img src="https://img.shields.io/badge/Maintained-Yes-cyan?style=flat-square">
   <img src="https://img.shields.io/badge/Written%20In-Ruby-blue?style=flat-square">
</p>

### [+] Description :
***Local2Internet is used to expose locally hosted website into all over internet.***

### [+] Installation

```sh
# Install deps
sudo apt install ruby python nodejs php wget curl unzip -y
npm install http-server -g

# Clone repo & run
git clone https://github.com/KasRoudra/Local2Internet && cd Local2Internet

ruby l2in.rb
```

On linux: try `sudo ruby l2in.rb` on first run


### Preview:

<img src="https://github.com/KasRoudra/Local2Internet/raw/main/main.jpg">

## Usage:

 - Enter the directory where website files are available.
 - Choose a hosting protocol.
 - Enter a port.
 - Use the generated link(s)!

## Features:
 - Multi-Tunneling & URL Scraping
 - Triple hosting protocol
 - Custom directory
 - Custom port
 - Environment & Dependency Verification:**
 - Binary Management: Ngrok, Cloudflared, and LocalXpose (`loclx`)
 - Interactive User Prompts
 - Local Server Launch


### Why Not Just Use Ngrok?

While Ngrok is the most famous tunneling tool, relying on it exclusively has several drawbacks that multi-tunneling scripts like Local2Internet aim to solve:

* **Authentication & Account Requirements:** Modern free-tier Ngrok requires signing up for an account and configuring an auth token just to run a basic tunnel. Tools like Cloudflare (`trycloudflare.com`) require **zero registration**, login, or API keys.
* **Redundancy and Reliability:** Ngrok's free public domains (`*.ngrok.io` or `*.ngrok-free.app`) are frequently flagged, rate-limited, or blocked by corporate firewalls, antivirus software, or ISPs. Having Cloudflare and LocalXpose as fallbacks ensures that if one service fails or gets blocked, your site remains accessible via another provider.
* **Bandwidth & Connection Limits:** Free Ngrok accounts have strict limits on concurrent connections and session timeouts. Cloudflare Tunnels generally offer higher reliability and throughput without hard throttling on ephemeral trial URLs.
* **ISP Filtering:** Certain mobile networks or regions block Ngrok's primary domain endpoints entirely; having alternative providers like Cloudflare or LocalXpose bypasses these regional blocks.


### [+] Find me on 

<a href="mailto://kasroudrakrd@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-kasroudrakrd@gmail.com-blue?style=for-the-badge&logo=gmail"></a>

<a href="https://m.me/KasRoudra" target="_blank"><img src="https://img.shields.io/badge/Messenger-KasRoudra-blue?style=for-the-badge&logo=messenger"></a>
