# Test Frontend

## 📋 Apa Saja yang Perlu Disiapkan?

Pastikan Anda sudah menginstal ini di komputer Anda:

Go (Golang): Versi 1.18 atau yang lebih baru.

Unduh Go https://go.dev/doc/install

Node.js & npm: Node.js .

Undun Nodejs https://nodejs.org/en/download

Nodemon: Alat untuk hot-reloading Go.

Cara instal:
```bash
npm install -g nodemon
```

---

## 🔧 Install

```bash
git clone https://github.com/alfarioekaputra/artajasa-test.git
cd artajasa-test
go mod tidy
npm install
```

## Running

## Dev

```bash
npm run dev
```

## Build
```bash
npm run tailwind:build
go build -o main.go
```

---

## 📁 Struktur Folder Proyek
main.go: File utama aplikasi Go Fiber.

views/: Folder berisi semua file HTML (.html).


public/: Folder berisi aset seperti gambar, CSS yang sudah jadi, dan JavaScript.

resource/css/app.css: File CSS utama tempat Anda mengatur Tailwind dan desain khusus.

public/css/output.css: File CSS yang dihasilkan oleh Tailwind.

public/images/: Folder untuk gambar-gambar yang dipakai di aplikasi (misalnya, modena.png, user.png, cart.png).

package.json: File pengaturan proyek Node.js dan perintah-perintah npm.

go.mod, go.sum: File untuk mengelola kebutuhan (dependensi) Go.
