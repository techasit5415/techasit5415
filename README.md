<div align="center">

# Techasit Vanitpattarakul

**Computer Science @ KMITL** · Infrastructure, Networking & Full-Stack Systems

[![CSNIS Org](https://img.shields.io/badge/CSNIS--CSKmitl-18181b?style=flat&logo=github&logoColor=white)](https://github.com/CSNIS-CSKmitl)
[![CSNIS Portal](https://img.shields.io/badge/csnis.cskmitl.com-18181b?style=flat&logo=svelte&logoColor=FF3E00)](https://csnis.cskmitl.com)
[![init.d](https://img.shields.io/badge/init--d.cskmitl.com-18181b?style=flat&logo=proxmox&logoColor=E57000)](https://init-d.cskmitl.com)
[![CS Colab](https://img.shields.io/badge/colab.cskmitl.com-18181b?style=flat&logo=jupyter&logoColor=F37626)](https://colab.cskmitl.com)
[![AI Passport](https://img.shields.io/badge/aipass.cskmitl.com-18181b?style=flat&logo=openai&logoColor=white)](https://aipass.cskmitl.com)
[![CS KMITL](https://img.shields.io/badge/CS_KMITL-E35205?style=flat)](https://www.cs.kmitl.ac.th/)

</div>

<br/>

I maintain the server cluster, firewall/network stack, storage infrastructure, and internal web & mobile platforms for the Department of Computer Science at KMITL (**[CSNIS](https://github.com/CSNIS-CSKmitl)**), covering virtualization, VLAN routing, and the services students and staff use every day.

---

### CS KMITL / CSNIS Production Ecosystem

All department platforms share a unified **PocketBase + KMITL OIDC** single sign-on core and run across our internal **Proxmox VE** cluster:

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/init.d">init.d</a></b> · <a href="https://init-d.cskmitl.com"><code>init-d.cskmitl.com ↗</code></a><br/>
      <sub>Self-service VM & LXC provisioning portal on Proxmox VE with integrated Web SSH and NoVNC console access.</sub><br/><br/>
      <code>SvelteKit</code> <code>Node.js</code> <code>Proxmox API</code> <code>PocketBase</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/csnis">CSNIS Portal</a></b> · <a href="https://csnis.cskmitl.com"><code>csnis.cskmitl.com ↗</code></a><br/>
      <sub>Department network portal, service directory, and interactive live network topology map.</sub><br/><br/>
      <code>Svelte 5</code> <code>SvelteKit</code> <code>Tailwind</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://colab.cskmitl.com">CS Colab</a></b> · <a href="https://colab.cskmitl.com"><code>colab.cskmitl.com ↗</code></a><br/>
      <sub>Multi-user containerized JupyterLab environment with NVIDIA RTX A2000 GPU pass-through, KMITL IAM SSO, and Colab-style automated idle resource culling.</sub><br/><br/>
      <code>JupyterHub</code> <code>DockerSpawner</code> <code>NVIDIA CUDA</code> <code>PocketBase</code> <code>Python</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/Printer-server">Printer Server</a></b> · <a href="https://printer.cskmitl.com"><code>printer.cskmitl.com ↗</code></a><br/>
      <sub>Web print queue, automated PDF page counting, and student print quota system hooked into Ubuntu CUPS.</sub><br/><br/>
      <code>SvelteKit</code> <code>TypeScript</code> <code>CUPS</code> <code>PocketBase</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/Booking">Room Booking</a></b> · <a href="https://booking.cskmitl.com"><code>booking.cskmitl.com ↗</code></a><br/>
      <sub>Computer lab and meeting room reservation platform with real-time schedule conflict detection.</sub><br/><br/>
      <code>Svelte 5</code> <code>SvelteKit</code> <code>PocketBase</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/brrow-item">Borrowly</a></b> · <a href="https://req.cskmitl.com"><code>req.cskmitl.com ↗</code></a><br/>
      <sub>Hardware & lab equipment borrowing system with stock tracking and two-stage approval workflows.</sub><br/><br/>
      <code>Svelte</code> <code>Vite</code> <code>Node.js</code> <code>PocketBase</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/Announcements">Announcements</a></b> · <a href="https://announcements.cskmitl.com"><code>announcements.cskmitl.com ↗</code></a><br/>
      <sub>Central broadcast hub delivering targeted pop-ups across department web services and push notifications to mobile.</sub><br/><br/>
      <code>Svelte 5</code> <code>SvelteKit</code> <code>PocketBase</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/android-cskmitl">CS KMITL Mobile</a> & Push Gateway</b> · <code>hub-api.cskmitl.com</code><br/>
      <sub>Unified Android client paired with an SSE realtime proxy and Python FCM push notification relay.</sub><br/><br/>
      <code>Kotlin</code> <code>Jetpack Compose</code> <code>Python</code> <code>FCM</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/CSNIS-CSKmitl/Ai-passport">AI Passport</a></b> · <a href="https://aipass.cskmitl.com"><code>aipass.cskmitl.com ↗</code></a><br/>
      <sub>AI access platform with KMITL OIDC, GPU-backed local LLM inference, per-user quotas, and time-slot reservations.</sub><br/><br/>
      <code>SvelteKit</code> <code>Ollama</code> <code>NVIDIA GPU</code> <code>PocketBase</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/AuthWeb">AuthWeb</a></b> · <code>Captive Portal</code><br/>
      <sub>KMITL WiFi authentication portal with Google OAuth and automated voucher generation via the OPNsense API.</sub><br/><br/>
      <code>TypeScript</code> <code>OPNsense API</code> <code>OAuth 2.0</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Docs & Handover Repository</b> · <a href="https://github.com/CSNIS-CSKmitl/Docs"><code>CSNIS-CSKmitl/Docs ↗</code></a><br/>
      <sub>Centralized architecture blueprints, deployment guides, and Thai handover documentation for all department systems.</sub><br/><br/>
      <code>Markdown</code> <code>Documentation</code> <code>CI/CD</code>
    </td>
    <td width="50%" valign="top">
      &nbsp;
    </td>
  </tr>
</table>

---

### Infrastructure, Storage & Network Operations

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Virtualization & Compute</b><br/>
      <sub>Multi-node <b>Proxmox VE</b> cluster running KVM virtual machines and LXC containers for production apps and student workloads with GPU passthrough.</sub>
    </td>
    <td width="50%" valign="top">
      <b>Network, Firewall & OpenVPN</b><br/>
      <sub><b>OPNsense</b> routing 10+ 802.1Q VLANs, NAT, Dnsmasq DNS/DHCP, Captive Portal, and <b>OpenVPN</b> remote access into internal VM subnets.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Storage & Department Cloud</b><br/>
      <sub>Centralized <b>TrueNAS</b> storage pool paired with high-performance <b>Cloudreve</b> (migrated from Nextcloud for lightweight footprint, high throughput, and fast chunked transfers) for department file management.</sub>
    </td>
    <td width="50%" valign="top">
      <b>Reverse Proxy & Traffic Gateway</b><br/>
      <sub>Production <b>Nginx</b> reverse proxy cluster managing SSL/TLS termination, HTTP/2, WebSocket multiplexing (JupyterHub / Web SSH consoles), and granular upstream proxying.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Observability & Compliance Logging</b><br/>
      <sub>Centralized <b>Syslog-ng + Promtail + Loki + Grafana</b> pipeline archiving firewall, NAT, DNS, and DHCP logs for Thai Computer Crime Act compliance.</sub>
    </td>
    <td width="50%" valign="top">
      <b>CI/CD & Runtime</b><br/>
      <sub>Self-hosted <b>GitHub Actions</b> Linux runners with automated build, SSH artifact delivery, and health-verified <b>PM2 / Docker</b> deployments.</sub>
    </td>
  </tr>
</table>

---

### Other Projects & Experiments

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/pdf-layout-analyzer">pdf-layout-analyzer</a></b><br/>
      <sub>CLI utility that audits PDF page margins, typography, and layout structure against academic report formatting standards.</sub><br/><br/>
      <code>Python</code> <code>CLI</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/AI-LLM">AI-LLM</a> / <a href="https://github.com/techasit5415/Ai-Rag">Ai-Rag</a></b><br/>
      <sub>Local LLM-powered Retrieval-Augmented Generation (RAG) chatbot running with GPU acceleration.</sub><br/><br/>
      <code>Python</code> <code>Local LLM</code> <code>RAG</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/StudentManagement">StudentManagement</a> & <a href="https://github.com/techasit5415/StudentManagement_backend">Backend</a></b><br/>
      <sub>Android app for student records backed by a Python FastAPI + PostgreSQL REST API (plus <a href="https://github.com/techasit5415/std-regis">std-regis</a>).</sub><br/><br/>
      <code>Kotlin</code> <code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/Pet">Desktop Pet (Kirby)</a></b><br/>
      <sub>Multi-monitor pixel-art Kirby desktop pet for Windows rendered purely in code without external image assets.</sub><br/><br/>
      <code>C#</code> <code>.NET 8</code> <code>WPF</code> <code>Win32 API</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/web-datamining">web-datamining</a> & <a href="https://github.com/techasit5415/sales_dashboard">sales_dashboard</a></b><br/>
      <sub>Web scraping, data mining pipelines, and interactive analytics dashboard projects.</sub><br/><br/>
      <code>Python</code> <code>Data Analysis</code>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/techasit5415/twocarsG">twocarsG</a> / <a href="https://github.com/techasit5415/MVC2025">MVC2025</a> / <a href="https://github.com/techasit5415/ComSci">ComSci</a></b><br/>
      <sub>Object-oriented programming, MVC architecture coursework, and 2D game projects written in Java.</sub><br/><br/>
      <code>Java</code> <code>OOP</code> <code>MVC</code>
    </td>
  </tr>
</table>

---

### Tech Stack

<div align="center">

[![Skills](https://skillicons.dev/icons?i=linux,docker,nginx,grafana,githubactions,svelte,ts,js,nodejs,py,fastapi,postgres,java,kotlin,cs,dotnet&perline=8)](https://github.com/techasit5415)

<br/>

[![Proxmox VE](https://img.shields.io/badge/Proxmox_VE-18181b?style=flat&logo=proxmox&logoColor=E57000)](https://www.proxmox.com/)
[![OPNsense](https://img.shields.io/badge/OPNsense-18181b?style=flat&logo=opnsense&logoColor=D94F00)](https://opnsense.org/)
[![TrueNAS](https://img.shields.io/badge/TrueNAS-18181b?style=flat&logo=truenas&logoColor=0095D5)](https://www.truenas.com/)
[![Nginx](https://img.shields.io/badge/Nginx-18181b?style=flat&logo=nginx&logoColor=009639)](https://nginx.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-18181b?style=flat&logo=jupyter&logoColor=F37626)](https://jupyter.org/)
[![NVIDIA CUDA](https://img.shields.io/badge/NVIDIA_CUDA-18181b?style=flat&logo=nvidia&logoColor=76B900)](https://developer.nvidia.com/cuda-zone)
[![OpenVPN](https://img.shields.io/badge/OpenVPN-18181b?style=flat&logo=openvpn&logoColor=EA7E20)](https://openvpn.net/)
[![Grafana Loki](https://img.shields.io/badge/Grafana_Loki_&_Promtail-18181b?style=flat&logo=grafana&logoColor=F46800)](https://grafana.com/oss/loki/)
[![Syslog-ng](https://img.shields.io/badge/Syslog--ng-18181b?style=flat&logo=linux&logoColor=FCC624)](https://www.syslog-ng.com/)
[![PocketBase](https://img.shields.io/badge/PocketBase-18181b?style=flat&logo=pocketbase&logoColor=B8DBE4)](https://pocketbase.io/)
[![PM2](https://img.shields.io/badge/PM2-18181b?style=flat&logo=pm2&logoColor=2B037A)](https://pm2.keymetrics.io/)
[![Python](https://img.shields.io/badge/Python-18181b?style=flat&logo=python&logoColor=3776AB)](https://www.python.org/)

</div>
