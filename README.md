1. alpine js itu seperti talwind. tailwind berupa cara instans untuk css. alpine itu cara instansnya javascript

2. jika menggunakan tidak menggunakan alpine js, kita membutuhkan javasacript terpisah dan syntax yang cukup panjang.

3. pengetahuan sebelum pake alpine:
 - sudah pernah belajar javascript dasar
 - DOM
 - jQuery

4. strukture si alpine
 - 2 cara install
 - 18 directive (directive ini sebuah fungsi yang bisa digunakan sebagai atribute pada htmlnya, ex: x-data, dll)
 - 9 magic properties
 - 3 global methods

5. cara install :
 - pake CDN. masukkan script ini di index.html (<script src="//unpkg.com/alpinejs" defer></script>)
 - install lewat npm (npm install alpinejs). lalu import ke aplikasi. 

6. State di Alpine Js
    - state adalah inti dari semua yang kita lakukan di Alpine Js.
    - data javascript yang di pantau perubahannya oleh alpine
    - bisa di buat local ataupun global (ex : x-data untuk local, dan Alpine.store() untuk global)

7. Alpine Js menawarkan banyak directive untuk memanipulasi DOM. Seperti:
    - x-text = untuk konten teks
    - x-html = untuk menyisipkan link url (inner html)
    - x-show / x-if = toggling element

    