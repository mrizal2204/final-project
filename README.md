# Final Project: Sign in & Sign up Page Nike.com E-Commerce Clone

Styling html menggunakan Tailwind.css dan Material Tailwind (Plugin Tailwind.css), yang diimplementasikan menggunakan [Tailwind CLI](https://tailwindcss.com/docs/installation).

Struktur file:

```
|-- src/
|  |-- image/
|  |   |-- jordan-logo.png
|  |   |-- nike-logo.png
|  |-- input.css
|  |-- output.css
|  |-- sign-in.html
|  |-- sign-out.html
|-- package-lock.json
|-- package.json
|-- README.md
|-- tailwind.config.js
```

File HTML & CSS utama adalah `sign-in.html`, `sign-up.html` dan `output.css`

- output.css: File css yang digunakan `sign-in.html` dan `sign-up.html`. Merupakan hasil css yang dibuat menggunakan Tailwind CLI.
- sign-in.html: File HTML untuk halaman Sign in.
- sign-up.html: File HTML untuk halaman Sign up.

## Cara menjalankan Tailwind CLI untuk mengkostumisasi CSS

1. Instal `tailwindcss` dan `@material-tailwind/html` melalui npm. Gunakan perintah berikut di terminal:

```
npm install
```

2. Selanjutnya jalankan perintah berikut ini di terminal:

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

3. selesai, mulailah mengkostumisasi syle pada element HTML dengan kelas bawaan Tailwind.
