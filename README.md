# Capstone-Shanghai---Team-H

# figma link:

https://www.figma.com/design/KDmhtvsydfgLMjfJu1OEoA/Ecommerce---Batch-4?node-id=29411-12622&p=f&t=9ePbne6TjEVd7mqP-0

# Git Quick Start - Capstone Shanghai Team H

```bash
# 1️⃣ Clone repository (hanya sekali di awal)
git clone https://github.com/WPH-Bootcamp/Capstone-Shanghai---Team-H.git
cd Capstone-Shanghai---Team-H

# 2️⃣ Install dependencies
npm install

# 3️⃣ Jalankan Tailwind
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

# 4️⃣ Mulai kerja / coding
git checkout main                # pindah ke branch main
git pull origin main             # update main terbaru
git checkout -b feature/nama-fitur   # buat branch baru

# 🔹 Sekarang mulai coding! Edit file di src/ sesuai task

# 5️⃣ Commit & push jika sudah selesai coding
git add .
git commit -m "Deskripsi perubahan"
git push origin feature/nama-fitur

# 6️⃣ Buat Pull Request → Review → Merge ke main
# ⚠️ Jangan coding langsung di main. Selalu lewat branch baru → PR → review
```

- Buka repo di GitHub → klik "Compare & pull request" atau "New pull request"
- Title: nama singkat perubahan, misal "Add navbar"
- Description: jelaskan perubahan/fix/fitur
- Base branch: main, Compare branch: feature/nama-fitur
- Klik "Create pull request"
- Tim lain review PR → setelah disetujui klik "Merge pull request"
- Hapus branch lama jika sudah tidak diperlukan
