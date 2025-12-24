cat << 'EOF' > README.md
<div align='center'>

# ✨ scrape-primbon

<img src="https://files.catbox.moe/x7emfw.jpeg" width="300"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=2800&pause=1200&color=FF69B4&center=true&vCenter=true&width=700&lines=Rumahmu+dimana%3F;Gua+mau+kesana;Disana+ada+siapa%3F;Kalo+sepi+main+sama+gua;Ah%2C+atas+bawah+cantik;Huh%2C+putar+badan+dikit;Ah%2C+goyang+tipis-tipis" />

<div style="display: flex; justify-content: center; gap: 10px; margin-top: 10px;">
  <a href="https://whatsapp.com/channel/0029Vb6ru1s2Jl87BaI4RJ1H">
    <img src="https://img.shields.io/badge/WhatsApp-Channel-25D366?logo=whatsapp&logoColor=white&style=for-the-badge" />
  </a>
</div>
</div>

Library Node.js untuk **scraping primbon online** 🔮.  
Mendukung berbagai fitur seperti ramalan jodoh 💑, arti nama 📝, rejeki 💰, mimpi 🌙, dan lainnya.

---

## 📦 Instalasi

npm install scrape-primbon

---

## ⚡ Penggunaan

### CommonJS

const { Primbon } = require('scrape-primbon');  
const primbon = new Primbon();

### ES Module

import { Primbon } from 'scrape-primbon';  
const primbon = new Primbon();

---

## 📝 Fitur dan Contoh

🔢 Nomer Hoki  
primbon.nomer_hoki('6288292024190').then(console.log);

🌙 Penafsiran Mimpi  
primbon.tafsir_mimpi('pipis').then(console.log);

💕 Ramalan Jodoh  
primbon.ramalan_jodoh('Rijalganzz','7','7','2005','Novia','1','12','2004').then(console.log);

🏝️ Ramalan Jodoh Bali  
primbon.ramalan_jodoh_bali('Rijalganzz','7','7','2005','Novia','1','12','2004').then(console.log);

💍 Ramalan Suami Istri  
primbon.suami_istri('Rijalganzz','7','7','2005','Novia','1','12','2004').then(console.log);

💌 Ramalan Cinta  
primbon.ramalan_cinta('Rijalganzz','7','7','2005','Novia','1','12','2004').then(console.log);

📝 Arti Nama  
primbon.arti_nama('Rijalganzz').then(console.log);

✅ Kecocokan Nama  
primbon.kecocokan_nama('Rijalganzz','7','7','2005').then(console.log);

❤️ Kecocokan Nama Pasangan  
primbon.kecocokan_nama_pasangan('Rijalganzz','Novia').then(console.log);

📅 Ramalan Tanggal Jadian Pernikahan  
primbon.tanggal_jadian_pernikahan('7','6','2019').then(console.log);

🏢 Sifat Usaha / Bisnis  
primbon.sifat_usaha_bisnis('7','7','2005').then(console.log);

💸 Rejeki Hoki Weton  
primbon.rejeki_hoki_weton('7','7','2005').then(console.log);

👔 Pekerjaan Weton  
primbon.pekerjaan_weton_lahir('7','7','2005').then(console.log);

---

## 🌟 Fitur Lainnya

Masih banyak fitur primbon lainnya. Silakan cek dokumentasi di kode atau repository GitHub.

---

## 📢 Saluran WhatsApp

https://whatsapp.com/channel/0029Vb6ru1s2Jl87BaI4RJ1H 📱

---

## 📄 Lisensi

MIT License
EOF