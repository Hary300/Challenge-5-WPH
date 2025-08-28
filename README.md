# Capstone-Shanghai---Team-H

---

# Figma link:

## https://www.figma.com/design/KDmhtvsydfgLMjfJu1OEoA/Ecommerce---Batch-4?node-id=29411-12622&p=f&t=9ePbne6TjEVd7mqP-0

---

# Git Quick Start

# 1️⃣ Clone repository (hanya sekali di awal)

```bash
git clone https://github.com/WPH-Bootcamp/Capstone-Shanghai---Team-H.git
cd Capstone-Shanghai---Team-H
```

# 2️⃣ Install dependencies

```bash
npm install
```

# 3️⃣ Jalankan Tailwind

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

# 4️⃣ Mulai kerja / coding

```bash
git checkout main                    # pindah ke branch main
git pull origin main                 # update main terbaru
git checkout -b feature/nama-fitur   # buat branch baru. contoh: git checkout -b feature/hary (nama branch terserah)
```

# 🔹 Sekarang mulai coding dibranch feature/hary ! Edit file di src/ sesuai task

# 5️⃣ Commit & push jika sudah selesai coding

```bash
git add .
git commit -m "Deskripsi perubahan"
git push origin feature/nama-fitur
```

# 6️⃣ Buat Pull Request → Review → Merge ke main

```bash
- Buka repo di GitHub → klik "Compare & pull request" atau "New pull request"
- Title: nama singkat perubahan, misal "Add navbar"
- Description: jelaskan perubahan/fix/fitur
- Base branch: main, Compare branch: feature/nama-fitur
- Klik "Create pull request"
- Tim lain review PR → setelah disetujui klik "Merge pull request"
- Hapus branch lama jika sudah tidak diperlukan
```

# ⚠️ Jangan coding langsung di main.

# ⚠️ Selalu coding lewat branch
