# Techasit Vanitpattarakul

CS student at **KMITL** working on department infrastructure, network systems, and internal web/mobile platforms under [**CSNIS-CSKmitl**](https://github.com/CSNIS-CSKmitl).

Most of my time goes into running our Proxmox cluster, OPNsense firewall/network stack, and building tools used by students and staff in the department.

### CS KMITL / CSNIS Projects ([GitHub Org](https://github.com/CSNIS-CSKmitl))

* [**init.d**](https://github.com/CSNIS-CSKmitl/init.d) ([init-d.cskmitl.com](https://init-d.cskmitl.com)) - Self-service VM \& LXC provisioning platform on Proxmox VE with Web SSH and NoVNC console
* [**csnis**](https://github.com/CSNIS-CSKmitl/csnis) ([csnis.cskmitl.com](https://csnis.cskmitl.com)) - Department network portal, service catalog, and live topology map
* [**Printer-server**](https://github.com/CSNIS-CSKmitl/Printer-server) ([printer.cskmitl.com](https://printer.cskmitl.com)) - Web print queue and page quota management hooked into Ubuntu CUPS
* [**Booking**](https://github.com/CSNIS-CSKmitl/Booking) ([booking.cskmitl.com](https://booking.cskmitl.com)) - Lab and meeting room reservation system
* [**brrow-item (Borrowly)**](https://github.com/CSNIS-CSKmitl/brrow-item) ([req.cskmitl.com](https://req.cskmitl.com)) - Department hardware \& equipment borrowing system
* [**Announcements**](https://github.com/CSNIS-CSKmitl/Announcements) ([announcements.cskmitl.com](https://announcements.cskmitl.com)) - Central announcement hub broadcasting across department web and mobile services
* [**AuthWeb**](https://github.com/techasit5415/AuthWeb) - KMITL WiFi authentication portal with Google OAuth and automated OPNsense voucher generation
* **Network, Firewall \& OpenVPN** - Department network segmentation (802.1Q VLANs), **OpenVPN** remote access gateway routed into internal VM subnets, DNS/DHCP, and centralized logging (Syslog / Promtail / Loki / Grafana) for Thai Computer Crime Act  compliance
* **CS KMITL Mobile** - Android client (Kotlin / Jetpack Compose) + Node/Python FCM push relay backed by PocketBase \& KMITL OIDC

### Other Repos \& Experiments

* [**pdf-layout-analyzer**](https://github.com/techasit5415/pdf-layout-analyzer) - Python CLI tool for checking PDF page margins, fonts, and layout against academic report rules
* [**AI-LLM**](https://github.com/techasit5415/AI-LLM) **/** [**Ai-Rag**](https://github.com/techasit5415/Ai-Rag) - Local LLM \& RAG chatbot experiments running with GPU acceleration
* [**StudentManagement**](https://github.com/techasit5415/StudentManagement) **\&** [**Backend**](https://github.com/techasit5415/StudentManagement_backend) - Kotlin Android app paired with a Python FastAPI + PostgreSQL backend (plus [std-regis](https://github.com/techasit5415/std-regis))
* [**Pet**](https://github.com/techasit5415/Pet) - Pixel-art Kirby desktop pet for Windows written in C# / WPF without external image assets
* [**web-datamining**](https://github.com/techasit5415/web-datamining) **\&** [**sales\_dashboard**](https://github.com/techasit5415/sales_dashboard) - Data scraping, analysis, and dashboard coursework in Python

### Stack & Tools

**Infra & Network**  
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Proxmox VE](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)](https://www.proxmox.com/)
[![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)](https://opnsense.org/)
[![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white)](https://openvpn.net/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)](https://nginx.org/)
[![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)](https://pm2.keymetrics.io/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)

**Monitoring & Logs**  
[![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)](https://grafana.com/)
[![Grafana Loki](https://img.shields.io/badge/Loki_&_Promtail-F46800?style=flat-square&logo=grafana&logoColor=white)](https://grafana.com/oss/loki/)
[![Syslog](https://img.shields.io/badge/Syslog--ng-00A98F?style=flat-square&logo=linux&logoColor=white)](https://www.syslog-ng.com/)

**Web & Backend**  
[![SvelteKit](https://img.shields.io/badge/Svelte_/_SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white)](https://svelte.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![PocketBase](https://img.shields.io/badge/PocketBase-B8DBE4?style=flat-square&logo=pocketbase&logoColor=black)](https://pocketbase.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

**Mobile & Desktop**  
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/compose)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![.NET / WPF](https://img.shields.io/badge/C%23_/_WPF-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)


