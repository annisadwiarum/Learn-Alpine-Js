- alpine js itu seperti talwind. tailwind berupa cara instans untuk css. alpine itu cara instansnya javascript

- jika menggunakan tidak menggunakan alpine js, kita membutuhkan javasacript terpisah dan syntax yang cukup panjang.

- pengetahuan sebelum pake alpine:
 - sudah pernah belajar javascript dasar
 - DOM
 - jQuery

- strukture si alpine
 - 2 cara install
 - 18 directive (directive ini sebuah fungsi yang bisa digunakan sebagai atribute pada htmlnya, ex: x-data, dll)
 - 9 magic properties
 - 3 global methods

- cara install :
 - pake CDN. masukkan script ini di index.html (<script src="//unpkg.com/alpinejs" defer></script>)
 - install lewat npm (npm install alpinejs). lalu import ke aplikasi. 
    import Alpine from 'alpinejs'
    window.Alpine = Alpine
    Alpine.start()
