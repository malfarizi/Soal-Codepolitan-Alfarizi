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

31. dd() digunakan untuk...

    a. Digunakan untuk sebagai helper untuk mengubah data
    
    b. Digunakan untuk sebagai helper untuk menambahkan data
    
    c. Digunakan untuk sebagai helper untuk menghapus data
    
    **d. Digunakan untuk sebagai helper untuk menampilkan data**
    
32. Singkatan dd() adalah...

    a. Dump and dump
    
    b. Die and die
    
    c. Drop and die
    
    **d. Dump and die**

33. Query Eloquent Laravel adalah...

    **a. Sebuah fitur untuk mengelola data yang ada pada database dengan mudah**
    
    b. Sebuah fitur untuk menampilkan data ke view
    
    c. Sebuah fitur untuk membuat model baru
    
    d. Semua salah
    
34. Method untuk menyimpan data product... 

```
    **a. Product::create([
        'title' => $this->title,
        'price' => $this->price,
        'decription' => $this->decription,]);**
   
   b. Product::put([
        'title' => $this->title,
        'price' => $this->price,
        'decription' => $this->decription,]);
   
   c. Product::add([
        'title' => $this->title,
        'price' => $this->price,
        'decription' => $this->decription,]);
   
   d. Product::get([
        'title' => $this->title,
        'price' => $this->price,
        'decription' => $this->decription,]);

```
 
35. Listener digunanakan untuk...

    a. Merupakan fungsi untuk menambah suatu kegiatan yang terjadi disuatu objek
    
    b. Merupakan fungsi untuk menghapus suatu kegiatan yang terjadi disuatu objek
    
    **c. Merupakan fungsi untuk merespon suatu kegiatan yang terjadi disuatu objek**
    
    d. Merupakan fungsi untuk mengubah suatu kegiatan yang terjadi disuatu objek
    
## Menambahkan Validasi Input di Livewire

36. Required pada validate digunakan untuk...
    
    **a. Form harus diisi**
    
    b. Form menerima inputan maksimal 180 mb
    
    c. Form terdapat jumlah minimal karakter yang dapat diinputkan
    
    d. Form terdapat jumlah batas maksimal karakter yang dapat diinputkan
    
    
37. Min pada validate digunakan untuk...

    a. Form menerima inputan hanya lampiran sebuah berkas
    
    b. Form menerima inputan maksimal 180 mb
    
    **c. Form terdapat jumlah minimal karakter yang dapat diinputkan**
    
    d. Form terdapat jumlah batas maksimal karakter yang dapat diinputkan
    
38. Max pada validate digunakan untuk...

    a. Form menerima inputan hanya lampiran sebuah berkas
    
    b. Form menerima inputan maksimal 180 mb
    
    c. Form terdapat jumlah minimal karakter yang dapat diinputkan
    
    **d. Form terdapat jumlah batas maksimal karakter yang dapat diinputkan**

39. Numeric pada validate digunakan untuk...
    
    **a. Hanya menerima inputan berupa nomor**
    
    b. Hanya menerima inputan berupa huruf alfabet
    
    c. Hanya meneripa inputan berupa simbol
    
    d. Hanya menerima inputan berupa file
    
40. Penulisan kode program yang benar untuk menampilkan peringatan di form title....
```
    a. @error('title')
        <span class="invalid-feedback"> 
           <strong> {$message} </strong>
        </span>
       @enderror
    
    **b.  @error('title')
        <span class="invalid-feedback"> 
           <strong> {{$message}} </strong>
        </span>
        @enderror**
```
    c. @error('title')
        <span class="invalid-feedback"> 
           <strong> [[message]] </strong>
        </span>
        @enderror
        
    d. @error('title')
        <span class="invalid-feedback"> 
           <strong> {{message}} </strong>
        </span>
        @enderror

## Menampilkan Notifikasi

41. Session flash adalah...

     a. Adalah sebuah session yang sifatnya permanen dan bisa di akases di halaman tertentu yang kita definisikan
     
    **b. Adalah sebuah session yang sifatnya sementara dan bisa di akases di halaman tertentu yang kita definisikan**
    
    c. Adalah sebuah session yang sifatnya sementara dan bisa di akases di semua halaman 
    
    d. Adalah sebuah session yang sifatnya permanen dan bisa di akases di semua halaman 
    
42. Di method mana untuk menuliskan helper session flash...

    a. Public function mount(){}
    
    b. Public function index(){}
    
    c. Public function render(){}
    
    **d. Public function productStoredHandler(){}**

43. Di bawah ini penulisan helper session flash yang benar...

```
    **a. session()->flash('message', ' Your product was stored');**

    b. session()->get->flash('message', ' Your product was stored');
    
    c. flash()->session('message', ' Your product was stored');
    
    d. session()->flash( $message , ' Your product was stored');
```

44. Bagaimana mendefinisikan session flash message pada view index...

```
    a. {{ session($message) }}
    
    b. {{ session(message) }}

    **c. {{ session('message') }}**
    
    d. {{ flash('message') }}
```

45. Class alert untuk menampilkan notifikasi sukses...

```
    a. <div class="alert alert-danger"
    
    **b. <div class="alert alert-success"**
    
    c. <div class="alert alert-triumph"
    
    d. <div class="alert alert-true"
```

## Membuat Fungsi Upload File di Livewire

46. Trait livewire untuk mengunggah gambar atau dokumen...

    a. UploadWithFiles
    
    b. FileUploads
    
    c. WithUploadsfile
    
    **d. WithFileUploads**
    
47. TemporaryUrl() digunakan untuk...

    a. Proses mengunggah file
    
    b. Untuk menunjukan menyimpan file yang diunggah 
    
    **c. Untuk menunjukan preview/pratinjau file yang diunggah sebelum disimpan**
    
    d. Semua salah
    
48. Validasi untuk menerima hanya masukan gambar adalah...

    **a. 'gambar' => 'image'**
    
    b. 'gambar' => 'file'
    
    c. 'gambar' => 'picture'
    
    d. 'gambar' => 'imagefile'
    
49. Tag untuk menentukan tinggi gambar...

    a. Width=""
    
    b. Size=""
    
    c. alt=""
    
    **d. Height=""**

50. Method untuk mendapatkan ekstensi dari gambar yang diunggah oleh pengguna...
```
    a. $this->image->OriginalExtensionClient();
    
    b. $this->image->ClientOriginalExtension();
    
    c. $this->image->getOriginalExtension();
    
    **d. $this->image->getClientOriginalExtension();**
```
## Membuat Form Update Product

51. Perintah untuk membuat component update dan disimpan di direktori product...

    a. Php artisan make:livewire update
    
    b. Php artisan make:livewire update.product
    
    **c. Php artisan make:livewire product.update**
    
    d. Php artisan make:livewire product
 
52. Method untuk mengubah data pada form update...

    a. Change
    
    **b. Update**
    
    c. Edit
    
    d. Create
    
53. Negasi (!) adalah...

    **a. Adalah pernyataan yang memiliki nilai kebenaran yang berlawanan dari pernyataan atau proposisi semula**
    
    b. Adalah pernyataan yang memiliki nilai kebenaran yang tidak berlawanan dari pernyataan atau proposisi semula
    
    c. Adalah pernyataan yang memiliki nilai salah yang berlawanan dari pernyataan atau proposisi semula
    
    d. Semua salah
    
54. Pemanggilan Title menggunakan perulangan foreach pada tabel di index.blade.php...

    a. {{ $product->$title }}
    
    **b. {{ $product->title }}**
    
    c. {{ $product=>title }}
    
    d. {{ product->title }}
    
55. Perintah untuk link storage pada laravel...

    **a. php artisan storage:link**
    
    b. php artisan storage
    
    c. php artisan make:link storage
    
    d. php artisan make:storage
    
## Membuat Fungsi Update Product
    
56. Cara pemanggilan model Product yang benar...

    a. Use Product;
    
    b. App\Product;
    
    **c. Use App\Product;**
    
    d. Use Public\App\Product;

57. Eloquent find berguna untuk...

    a. Perintah mengambil data sesuai dengan seconday key table
     
    **b. Perintah mengambil data sesuai dengan primary key table**
    
    c. Perintah mengambil data sesuai dengan data yang baru diinput ke dalam table database
    
    d. Semua salah

58. Method untuk menghapus gambar product yang lama...

    a. Storage::disk('public')->dump($product->image);
    
    b. Storage::disk('public')->drop($product->image);
    
    c. Storage::disk('public')->update($product->image);
    
    **d. Storage::disk('public')->delete($product->image);**
    
 59. Slug adalah...
 
    **a. Fungsi slug untuk memanggil data dengan judul, dan bisa juga untuk membuat url menjadi SEO Friendly**
    
    b. Fungsi slug untuk menjadikan data judul menjadi numeric
    
    c. Mengkonversi seluruh inputan menjadi hasing
    
    d. Semua salah
    
 60. Uniqid digunakan untuk...

    a. Untuk mendapatkan data sesuai id
    
    b. Untuk menghapus data lama
    
    c. Untuk mengubah data integer menjadi string
    
    **d. Untuk menghasilkan Id yang unik**

## Membuat Fungsi Delete Product

61. Penulisan kode program event click pada tombol delete Product...
```
    **a. <button wire:click="deleteProduct({{ $product->id }})" class="btn btn-sm btn-danger">Delete</button>**
    
    b. <button click:wire="deleteProduct({{ $product->id }})" class="btn btn-sm btn-danger">Delete</button>
    
    c. <button click="deleteProduct({{ $product->id }})" class="btn btn-sm btn-danger">Delete</button>
    
    d. <button wire:klik="deleteProduct({{ $product->id }})" class="btn btn-sm btn-danger">Delete</button>
```

62. Pada tombol delete btn-danger akan menjadikan tombol berwarna...

    a. Hijau
    
    b. Ungu
    
    c. Biru
    
    **d. Merah**
    
63. Isi parameter pada method deleteProduct()...

    a. $idProduct
    
    b. $title
    
    c. $price
    
    **d. $productId**

64. Method untuk menghapus data product...

    a. product->remove();
    
    b. product->dump();
    
    c. product->drop();
    
    **d. $product->delete();**
    
65. Tag html untuk membuat tombol...
```
    a. <switch>
    
    **b. <button>**
    
    c. <knob>
    
    d. <lever>
```

# Halaman Shop

## Membuat Halaman Daftar Product

66. Perintah untuk membuat component index di dalam folder shop...

    a. php artisan make:livewire shop
    
    b. php artisan make:livewire index.shop
    
    c. php artisan make:livewire index
    
    **d. php artisan make:livewire shop.index**

67. Tag html ```<li>``` berguna untuk...

    a. Untuk membuat kolom baru
    
    b. Untuk membuat header dari tabel
    
    c. Untuk membuat ordered list
    
    **d. Untuk membuat list item**

68. Pada view index terdapat class container, container digunakan untuk...

    **a. Untuk wadah yang menampung semua element grid sistem dari bootstrap**
    
    b. Untuk wadah yang menampung semua javascript sistem dari bootstrap
    
    c. Untuk wadah yang menampung semua controller pada laravel
    
    d. Semua salah
    
69. Perulangan apa yang digunakan untuk menampilkan product...

    **a. Foreach**
    
    b. For
    
    c. While
    
    d. Do while
    
70. Letak view dari index shop...

    a. Resources/views/shop/index.blade.php
    
    b. Resources/livewire/shop/index.blade.php
    
    c. Resources/views/shop/livewire/index.blade.php
    
    **d. Resources/views/livewire/shop/index.blade.php**

## Membuat Helper Shopping Cart

71. Setter adalah...

    a. Adalah method yang digunakan untuk menyimpan data ke tabel database
    
    b. Adalah method yang digunakan untuk menyisipkan satu atau lebih ke elemen terakhir dari array
    
    **c. Adalah method yang digunakan untuk memberikan nilai pada attribute**
    
    d. Adalah method yang digunakan untuk mendapatkan nilai dari attribute

72. Getter adalah...

    **a. Getter digunakan untuk mendapatkan nilai dari attribute**
    
    b. Adalah method yang digunakan untuk memberikan nilai pada attribute
    
    c. Adalah method yang digunakan untuk menyisipkan satu atau lebih ke elemen terakhir dari array
    
    d. Adalah method yang digunakan untuk menyimpan data ke tabel database

73. Array_splice() digunakan untuk...

    a. Digunakan untuk mendapatkan nilai dari attribute
    
    b. Digunakan untuk menyisipkan satu atau lebih ke elemen terakhir dari array
    
    **c. Digunakan untuk menghapus elemen yang dipilih dari array dan menggantinya dengan elemen baru**
    
    d. Digunakan untuk mendapatkan sebuah value yang ada di array, dan memunculkan output berupa key yang memiliki value yang di cari

74. Array_search() digunakan untuk...

    a. Digunakan untuk menghapus elemen yang dipilih dari array dan menggantinya dengan elemen baru
    
    b. Digunakan untuk mendapatkan nilai dari attribute
    
    **c. Digunakan untuk mencari sebuah value yang ada di array, dan memunculkan output berupa key yang memiliki value yang di cari**
    
    d. Semua salah
    
75. Penulisan method get untuk mendapatkan data yang ada di cart...
```

    **a. Public function get(){
       return request()->session()->get('cart')
    }**
    
    b. Public function get(){
       return request()->session->get('cart')
    
    c. Public function get(){
       return request()->get('cart')
    
    d. Public function get(){
       return session()->return()->get('cart')
    
```
## Cara Membuat Facade di Laravel

76. Penulisan yang benar untuk import facade...

    a. Use Illuminate\Support\Facade;
    
    b. Use Illuminate\Facades\Facade;
    
    c. Use Facade:
    
    **d. Use Illuminate\Support\Facades\Facade;**

77. Namespace dari facade...

    **a. Namespace App\Facades;**
    
    b. Namespace Facades;
    
    c. Namespace App\Model\Facades;
    
    d. Namespace App\livewire\Facades;
    
78. Perintah untuk membuat service provider baru...

    **a. Php artisan make:provider nama_provider**
    
    b. Php artisan make:storage nama_provider
    
    c. Php artisan make:link nama_provider
    
    d. Php artisan provider nama_provider

79. Penulisan Aplication Service Provider untuk cart...

    a. App\Providers\CartServiceProvider
    
    **b. App\Providers\CartServiceProvider::class**
    
    c. App\CartServiceProvider::class
    
    d. Providers\CartServiceProvider::class

80. Aliases untuk cart...
    
    a. 'Cart' > App\Facades\Cart::class
    
    b. 'Cart' -> App\Facades\Cart::class
    
    **c. 'Cart' => App\Facades\Cart::class**
    
    d. 'Cart' => App\Facades\Facade\Cart::class

## Implementasi Fungsi Add To Cart

81. Parameter yang digunakan pada method addToCart...

    a. $price
    
    b. $product
    
    c. $title
    
    **d. $productId**

82. Method untuk menambahkan product ke cart...

    a. Cart::addto($product);
    
    b. Cart::push($product);
    
    c. Cart::get($product);
    
    **d. Cart::add($product);**

83. Perintah untuk membuat component cartnav di dalam folder shop... 

    a. php artisan make:livewire cartnav
    
    **b. php artisan make:livewire shop.cartnav**
    
    c. php artisan make:livewire shop->cartnav
    
    d. php artisan make:component shop.cartnav

84. Count digunakan untuk...

    a. Untuk menghapus data product yang ada di shopping cart
    
    b. Untuk menambah product ke dalam shopping cart
    
    **c. Untuk menghitung data product yang masuk ke shopping cart**
    
    d. Untuk menampilkan data product yang ada di shopping cart

85. Penulisan kode program untuk melihat berapa data product yang ada pada session cart...

    **a. ( {{ $cartTotal }} )**
    
    b. count->( {{ $cartTotal }} )
    
    c. ( {{ $Total }} )
    
    d. ( {{ $cart }} )
    
# Halaman Shopping Cart
## Membuat Halaman Shopping Cart

86. Perintah untuk membuat component cart di dalam folder shop... 

    a. Php artisan make:livewire cart.shop
    
    b. Php artisan make:controller shop.cart
    
    c. Php artisan make:livewire cart
    
    **d. Php artisan make:livewire shop.cart**

87. Tag html untuk membuat tabel
```
    a. <table>
    
    b. <thead>
    
    c. <tfoot>
    
    d. <border>
```
88. Thead berguna untuk...

    **a. Berguna untuk mengelompokkan isi atau konten yang berada di bagian atas (kepala) pada sebuah tabel**
    
    b. Berguna untuk mengelompokkan isi atau konten yang berada di bagian bawah (kaki) sebuah tabel
    
    c. Berguna untuk mengelompokkan konten atau isi yang terletak pada bagian tengah (tubuh) sebuah tabel
    
    d. Berguna untuk mengelompokkan isi atau konten yang berada di bagian atas (kepala) dan bawah (kaki) pada sebuah tabel

89. Tfoot berguna untuk

    a. Berguna untuk mengelompokkan isi atau konten yang berada di bagian atas (kepala) pada sebuah tabel
    
    **b. Berguna untuk mengelompokkan isi atau konten yang berada di bagian bawah (kaki) sebuah tabel**
    
    c. Berguna untuk mengelompokkan konten atau isi yang terletak pada bagian tengah (tubuh) sebuah tabel
    
    d. Berguna untuk mengelompokkan isi atau konten yang berada di bagian atas (kepala) dan bawah (kaki) pada sebuah tabel

90. Penulisan route untuk halaman cart...

    **a. Route::livewire('/cart', 'shop.index')->name('shop.cart');**
    
    b. Route::get('/cart', 'shop.index')->name('shop.cart');
    
    c. Route::livewire->get('/cart', 'shop.index')->name('shop.cart');
    
    d. Route::post('/cart', 'shop.index')->name('shop.cart');
    
## Membuat Fungsi Remove Product

91.

92.

93.

94.

95. 
