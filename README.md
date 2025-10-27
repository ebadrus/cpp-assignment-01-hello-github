# cpp-assignment-01-hello-github
Tugas ke-1: Mengenal GitHub dan membuat program pertama "Hello, GitHub"

## Tujuan Pembelajaran
- Mengenal dasar penggunaan Git & GitHub.
- Mengupload dan mengedit file di repositori pribadi.
- Menggunakan commit dan push untuk melacak perubahan.

---

## Instruksi Tugas
- Join GitHub Classroom menggunakan link yang telah dibagikan
- Buat program C++ dengan output "Hello, GitHub!"
- Jalankan dari gitbash / terminal / cmd satu persatu saja:
```bash
git init
curl https://raw.githubusercontent.com/github/gitignore/main/C++.gitignore -o .gitignore
git add .
git commit -m "Menampilkan Hello GitHub"
git push
```
- Cek di GitHub kalau kodenya sudah tampil di repo
- Jangan ubah struktur folder


## 🧰 **Tambahin di `.gitignore` kalau pake VSCode**

```gitignore
# Editor settings
.vscode/
.idea/
