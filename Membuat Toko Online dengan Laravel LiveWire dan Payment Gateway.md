# Perkenalan dan Persiapan
## Persiapan Project

1. Apa fungsi Model Di Laravel...

    a. Model adalah bagian yang mengatur tampilan ke pengguna, Tampilan view berupa halaman web

    **b. Model adalah bagian yang berkomunikasi dengan database. Biasanya model berisi fungsi-fungsi yang membantu dalam pengelolaan  basis data, seperti memasukan data ke basis data, pembaruan data, dan lain-lain**

    c. Model adalah yang menjembatani antara model dan view

    d. Model berguna untuk menampilkan tampilan

2. Perintah untuk membuat model baru...

     
   **a. Php artisan make:model nama_model**
    
    b. Php artisan model:make nama_model
    
    c. Php artisan new:model nama_model
    
    d. Semua salah

3. Nullable adalah...

    **a. Nullable adalah type yang digunakan untuk mewakili kondisi yang tidak mempunyai nilai**
    
    b. Nullable adalah type yang digunakan untuk mewakili kondisi yang mempunyai nilai
    
    c. Nullable adalah type yang harus memasukan nilai
    
    d. Semua salah
    
4.  Apa itu Seeder...

    a. Seeder adalah penghubung antara Model dengan View

    b. Seeder dapat digunakan untuk berkomunikasi dengan database 

    c. Seeder digunakan untuk menampilkan halaman

    **d. Seeder dapat digunakan untuk membuat sample data atau data dummy untuk mengisi database yang telah dibuat**
    
5.  Berikut cara pemanggilan model Product yang benar adalah...

    **a. Use App\Product;**

    b. Use App\Test\Product;

    c. Use Product;

    d. Use Public\Model\Product;

## Mengenal Livewire

6. Perintah untuk install Livewire...

    a. Composer require livewire
    
    b. Install livewire
    
    **c. Composer require livewire/livewire**
    
    d. Composer require download/livewire
    
7. Perintah membuat component baru pada commandline...
 
    **a. php artisan make:livewire nama_component**
    
    b. php artisan make:component nama_component
    
    c. php artisan make:livewirecomponent nama_component
    
    d. php artisan component nama_component
 
8. Cara pemanggilan component counter livewire di view...
 
    a. @include('counter')
    
    b. @extends('counter')
    
    c. @get('counter')
   
    **d. @Livewire('counter')**
    
9. Model Factory adalah...
    
    a. Untuk berkomunikasi dengan database
    
    **b. Mengisi record tabel database secara acak untuk digunakan sebagai dummy data atau data sebagai testing**
    
    c. Penghubung antara view dengan model
    
    d. Fungsi yang berguna untuk menampilkan konten pada halaman
    
10. Perintah membuat file UserSeeder baru...
 
    a. git artisan make:seed UserSeeder
    
    b. artisan make:seeder UserSeeder
 
    **c. php artisan make:seed UserSeeder**
 
    d. php artisan make new:seed UserSeeder
    
# Managament Project
## Menampilkan Data Produk dengan Paginate di Livewire

11. Di bawah ini perintah untuk membuat component product yang disimpan di dalam folder component product...

    **a. php artisan make:livewire product.index**
    
    b. php artisan make:livewire product
    
    c. php artisan make:controller product
    
    d. php artisan make:newlivewire product.index
 
12. Di mana letak file component index yang telah dibuat...

    a. Resources\Http\Livewire\Product\Index.php
    
    b. Database\Http\Livewire\Product\Index.php
    
    **c. App\Http\Livewire\Product\Index.php**
    
    d. Public\Http\Livewire\Product\Index.php
    
13. Penulisan kode untuk menampilkan tombol paginate pada product adalah...

    a. {{ $products->links{} }}
    
    b. {{ $products->link() }}
    
    c. {{ $products->links }}
    
    **d. {{ $products->links() }}**
   
14. Pagination adalah...

    **a. Proses membagi konten menjadi halaman terpisah**
    
    b. Proses menampilkan seluruh konten 
    
    c. Proses untuk menampilkan seluruh isi tabel pada database berdasarkan 10 data
    
    d. Semua salah
    
15.  Method paginate(10) pada product berguna untuk...

    **a. Untuk menampilkan 10 per halaman data product**
    
    b. Untuk memasukan 10 data ke tabel database product
    
    c. Untuk menghapus 10 data product
    
    d. Untuk mengubah 10 data product
    

## Membuat Index Paginate Menjadi Dinamis
    
16. Fungsi tag Div adalah...

    **a. Div digunakan untuk mengelompokkan elemen atau tag-tag agar menjadi suatu grup**
   
    b. Digunakan untuk membuat objek form yang berupa list pilihan yang dapat dipilih oleh user
    
    c. Berfungsi untuk membuat baris baru
    
    d. Berfungsi untuk membuat kolom baru
   
17. Pada view index class row berguna untuk...
    
    a. Berfungsi untuk membuat kolom baru
    
    b. Berfungsi untuk membuat baris dan kolom baru
    
    **c. Berfungsi untuk membuat baris**
    
    d. Semua salah
 
18.  Pada view index select berguna untuk...

    **a. Digunakan untuk membuat objek form yang berupa list pilihan yang dapat dipilih oleh user**
    
    b. Berfungsi untuk membuat baris dan kolom baru
    
    c. Berfungsi untuk membuat baris
    
    d. Semua salah
    
19. 

20.

## Membuat Fitur Pencarian Data di Livewire

21. Fungsi Where digunakan untuk...
    
    **a. Untuk pencarian data yang sesuai atau mirip apa yang dicari**

    b. Untuk menampilkan data terbaru

    c. Untuk mencari data yang tidak sesuai dengan yang dicari

    d. Untuk mencari data yang baru dimasukan
    
22. Pada view index class col berguna untuk...
    
    **a. Berfungsi untuk membuat kolom baru**
    
    b. Berfungsi untuk membuat baris dan kolom baru
    
    c. Berfungsi untuk membuat baris
    
    d. Semua salah
    
23. Fungsi $this adalah...

    a. Digunakan sebagai penunjuk kepada model, ketika kita mengaksesnya dari dalam class
    
    b. Digunakan sebagai penunjuk kepada variabel, ketika kita mengaksesnya dari dalam class
    
    **c. Digunakan sebagai penunjuk kepada objek, ketika kita mengaksesnya dari dalam class**
    
    d. Digunakan sebagai penunjuk kepada component, ketika kita mengaksesnya dari dalam class

24. Latest() berguna untuk...
    
    **a. Mengambil data yang paling baru dari tabel database dan mengurutkannya**
    
    b. Mengambil data yang paling lama dari tabel database
    
    c. Mengambil data hanya satu record dari tabel database
    
    d. Semua salah
    
25. Apa kegunaan dari placeholder...

    a. Berguna untuk penamaan name pada form
    
    b. Berguna untuk membuat tulisan menjadi tidak terlihat
    
    **c. Berguna untuk membuat tulisan dengan tujuan memberikan penamaan pada form**
    
    d. Semua salah
 

## Membuat Form Create Product

26. Perintah di bawah ini untuk membuat component create yang disimpan di folder product...
    
    a. Php artisan livewire product.create
    
    b. Php artisan livewire create.product
    
    c. Php artisan make:livewire create.product
    
    **d. Php artisan make:livewire product.create**

27. Apa itu Bootstrap...

    a. Bootstrap merupakan sebuah library framework CSS yang telah dibuat khusus uintuk mengembangkan back end sebuah website
    
    **b. Bootstrap merupakan sebuah library framework CSS yang telah dibuat khusus uintuk mengembangkan front end sebuah website**
    
    c. Bootstrap merupakan sebuah library framework CSS yang telah dibuat khusus uintuk mengembangkan front end dan back end sebuah website
    
    d. Semua salah
    
28. Input type untuk gambar...
    
    a. Input type="text"
    
    **b. Input type="file"**
    
    c. Input type="image"
    
    d. Input type="photo"

29. Input type untuk masukan teks adalah...

    **a. Input type="text**"
    
    b. Input type="file"
    
    c. Input type="image"
    
    d. Input type="photo"

30. $emit digunakan untuk...

    **a. Untuk berkomunikasi antar component**
    
    b. Untuk menampilkan component lain
    
    c. Untuk membuat component baru
    
    d. Semua salah
    
## Menyimpan Data Product Secara Realtime

