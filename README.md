🚀 Panduan Setup Microsoft Learn MCP Server & CLI di VS Code
Selamat datang di repositori ini! Panduan ini dibuat untuk membantu rekan-rekan mahasiswa dan developer yang ingin mengintegrasikan dokumentasi resmi Microsoft Learn langsung ke dalam environment coding (VS Code) menggunakan Model Context Protocol (MCP).

Dengan setup ini, AI Anda dapat membaca konteks dan mencari solusi error atau dokumentasi terbaru dari Microsoft Learn secara real-time!

🌟 Mengapa Ini Penting? (Value Proposition)
Produktivitas: Tidak perlu lagi bolak-balik antara VS Code dan browser saat mencari dokumentasi.

Akurasi AI: Mengurangi "halusinasi" AI karena sumber jawabannya langsung diambil dari dokumentasi terpercaya Microsoft.

Praktis: Bisa dijalankan instan menggunakan Command Line Interface (CLI).

🛠️ Prasyarat
Sebelum memulai, pastikan Anda sudah memiliki:

Visual Studio Code (VS Code) terinstal di komputer Anda.

Node.js (untuk menjalankan perintah npm atau npx di terminal).

📖 Langkah-Langkah Instalasi & Penggunaan
Langkah 1: Akses Dokumentasi Resmi MCP Microsoft Learn
Langkah pertama adalah memahami dasar-dasar MCP dari dokumentasi resmi Microsoft.

Buka tautan panduan resmi ini: Microsoft Learn MCP Support (Login/Sign-in terlebih dahulu agar progres belajar Anda tersimpan).

Pada halaman tersebut, cari dan klik tombol "Get started in VS Code".

Jika VS Code sudah terinstal, browser akan otomatis meminta izin untuk membuka aplikasi VS Code Anda.

Langkah 2: Menggunakan Learn CLI (Command Line Interface)
Proses instalasi akan mengarahkan Anda ke repositori resmi GitHub microsoftdocs/mcp. Anda bisa langsung mencoba berinteraksi dengan Microsoft Learn melalui terminal VS Code.

Buka terminal di VS Code (Ctrl + ~), lalu pilih salah satu cara berikut:

Opsi A: Jalankan Secara Instan (Tanpa Instalasi)
Jika Anda hanya ingin mencoba sesekali tanpa menginstal, gunakan perintah ini:

Bash
npx @microsoft/learn-cli search "azure functions timeout"
Opsi B: Instalasi Global (Direkomendasikan)
Jika Anda ingin menggunakannya secara permanen dan lebih cepat, instal CLI secara global di komputer Anda:

Bash
npm install -g @microsoft/learn-cli
Setelah terinstal, Anda bisa mencari dokumentasi kapan saja hanya dengan perintah mslearn:

Bash
mslearn search "azure functions timeout"
(Perintah di atas akan secara otomatis mencari dan merangkum artikel terkait "azure functions timeout" langsung dari Microsoft Learn).

Langkah 3: Menjadikan MCP Server sebagai AI Agent di VS Code
Agar pengalaman coding Anda lebih canggih, Anda bisa menjadikan MCP ini sebagai agen AI di VS Code Anda.

Buka tab Ekstensi (Extensions) atau menu Chat di VS Code.

Klik ikon Roda Gigi (Settings/Gear ⚙️).

Pilih opsi "MCP Server".

Konfigurasikan dengan nama (misal: microsoft-learn) dan URL yang sesuai dengan panduan.

Selesai! Kini agen AI di VS Code Anda terhubung langsung dengan database ilmu Microsoft Learn.

🤝 Mari Berkontribusi!
Proyek panduan ini bersifat terbuka (open-source). Jika Anda menemukan cara yang lebih efisien atau ingin menambahkan studi kasus penggunaan perintah CLI lainnya, silakan ajukan Pull Request (PR).

Jangan lupa tingkatkan skill Anda dengan mempelajari modul-modul gratis seputar AI dan Cloud di Microsoft Learn!

👉 https://learn.microsoft.com/en-us/users/HelgaRizkaPutraPrayoga-3765/?wt.mc_id=studentamb_664597
👉 https://egha-app.web.id/
