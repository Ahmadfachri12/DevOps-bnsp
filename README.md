# Implementasi Pipeline CI/CD dan Sistem Monitoring Infrastruktur 🚀

## 🏗️ Arsitektur Sistem
Berikut adalah alur kerja otomatisasi (CI/CD) dan sistem monitoring yang diimplementasikan:

![DevOps Workflow Diagram](img/workflow-diagram.png)

---

## 📊 Hasil Monitoring
Berikut adalah tampilan dashboard monitoring resource server menggunakan Grafana yang menunjukkan penggunaan CPU dan Memori secara real-time:

![Grafana Monitoring Dashboard](img/grafana-dashboard.png)

Proyek ini merupakan implementasi alur kerja DevOps modern untuk aplikasi berbasis Python Flask. Mencakup proses kontainerisasi menggunakan Docker, otomatisasi deployment melalui GitHub Actions ke VPS, serta sistem observabilitas menggunakan Prometheus dan Grafana.

---

## 🛠️ Teknologi & Tools
* **Aplikasi:** Python Flask
* **Kontainerisasi:** Docker & Docker Compose
* **CI/CD:** GitHub Actions (SSH Deployment)
* **Monitoring:** Prometheus & Node Exporter
* **Visualisasi:** Grafana Dashboard
* **Infrastruktur:** Cloud VPS / AWS EC2

---

## 🏗️ Arsitektur Sistem
Proyek ini mengintegrasikan siklus hidup pengembangan perangkat lunak (SDLC) yang otomatis:
1.  **Code:** Pengembang melakukan perubahan kode di lokal.
2.  **Push:** Kode dikirim ke GitHub.
3.  **Deploy:** GitHub Actions secara otomatis melakukan SSH ke VPS, menarik kode terbaru, dan melakukan re-build container.
4.  **Monitor:** Resource server dipantau secara real-time melalui dashboard Grafana.        
