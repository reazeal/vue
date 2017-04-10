Cara untuk menampilkan "Hello World" menggunakan VueJS
1. Buat file index.html.
Lalu isi file index.html tersebut dengan script 
```php
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Untitled Document</title>
</head>
<body>
	<div id="contoh-1">
  		Hello {{ name }}!
	</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.2.6/vue.min.js"></script>
<script src="satu.js" ></script>
</body>
</html>
```
2. Buat file satu.js.
Lalu isi file tersebut dengan script
```php
// Model
var exampleData = {
  name: 'World'
}
// "ViewModel"
// yang menghubungkan antara view dan model
var exampleVM = new Vue({
  el: '#contoh-1',
  data: exampleData
})
```
3. Jalankan file index.html
