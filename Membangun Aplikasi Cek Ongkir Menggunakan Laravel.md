# Membangun Aplikasi Cek Ongkir Menggunakan Laravel

## Persiapan Model Migration Project
1. Framework apa yang digunakan untuk project ini...
   
     **a. Laravel**
   
    b. CodeIgniter
   
    c. Vue

    d. React

2. Layanan pihak ketiga apa yang digunakan untuk membangun aplikasi cek ongkir ini...

    a. Shipper

    **b. RajaOngkir** 

    c. IndoOngkir

    d. Woongkir

3. Apa yang dimaksud dengan Database...
    
    **a. Database merupakan kumpulan informasi atau data yang disimpan dalam sistem sebuah komputer**

    b. Perintah untuk import Migration ke Database

    c. Membuat controller pada aplikasi

    d. Untuk menampilkan semua data pada database 

4. DBMS apakah yang digunakan untuk membangun aplikasi cek ongkir ini...
    
    a. PostgreSQL

    b. SQLite

    c. IBM DB2

    **d. MySql**

5. Apakah fungsi Model di Laravel...

    a. Model adalah bagian yang mengatur tampilan ke pengguna, Tampilan view berupa halaman web

    **b. Model adalah bagian yang berkomunikasi dengan database. Biasanya model berisi fungsi-fungsi yang membantu dalam pengelolaan  basis data, seperti memasukan data ke basis data, pembaruan data, dan lain-lain**

    c. Model adalah yang menjembatani antara model dan view

    d. Model berguna untuk menampilkan tampilan
6. Bagaimana cara mengintall laravel menggunakan composer...

    a.	composer project-create --prefer-dist laravel/laravel blog
    
    **b.	composer create-project --prefer-dist laravel/laravel blog**
    
    c.	composer laravel/laravel create-project --prefer-dist blog
    
    d.	composer --prefer-dist create-project laravel/laravel blog

## Import Data Seed Menggunakan File JSON

7. Apa itu Seeder...

    a. Seeder adalah penghubung antara Model dengan View

    b. Seeder dapat digunakan untuk berkomunikasi dengan database 

    c. Seeder digunakan untuk menampilkan halaman

    **d. Seeder dapat digunakan untuk membuat sample data atau data dummy untuk mengisi database yang telah dibuat**
    
8. Berikut cara pemanggilan model provinsi yang benar adalah...

    **a. Use App\Provinsi**

    b. Use App\Test\Provinsi

    c. Use Provinsi

    d. Use Public\Model\Provinsi

9. Dibawah ini mana penulisan kode yang benar untuk pemanggilan file provinsi.json yang sudah dibuat ke dalam file seeder provinsi...

    **a. $file = file_get_contents(base_path('/database/provinsi.json'));**

    b. $file = file_get_client_originname(base_path('/database/provinsi.json'));

    c. $file = file_get_contentoriginal(base_path('/database/provinsi.json'));

    d. $file = get_original_file(base_path('/database/provinsi.json'));

10. Json_decode($file, true); berguna untuk...

   **a. Menjadikan data yang dipanggil sebagai array**

    b. Mengkonversi data menjadi objek

    c. Untuk menghasilkan Json dari array

    d. Menjadikan data yang dipanggil sebagai boolean

11. Method insert pada ProvinceSeeder.php digunakan untuk...

    **a. Memasukan data provinsi yang telah dibuat untuk di masukan ke dalam tabel database**

    b. Menghapus data provinsi yang ada di dalam tabel database

    c. Menampilkan data provinsi ke halaman utama

    d. Method untuk mengubah data provinsi

12. Perintah untuk menjalankan migration adalah...

    a. php artisan make:migration

    b. php artisan migration

    c. php artisan make=migration

    **d. php artisan migrate**

## Membuat Halaman Homepage Cek Ongkir

13. Berikut cara mengarahkan ke route yang secara otomatis dibuat oleh auth scaffolding
    
    **a. Route::get('/', function () {
        return redirect('/home;);
    });**
    
    b. Route::get('/', function () {
        return view('/home;);
    });

    c. Route::get('/', function () {
        return redirect->back();
    });

    d. Route::get('/home', function () {
        return redirect('/;);
    });
14. Yang berfungsi sebagai jembatan antara model dan view adalah...

    a.	Middleware
    
    **b.	Controller**
    
    c.	Routes
    
    d.	Migration 
     
15. Bagaimana cara kita untuk memberikan efek rata tengah pada baris text...
```  
    **a. <style>
            .ongkir-header {
                padding: 3rem 1.5rem;
                text-align : center;
            }
        </style>**

    b. <style>
            .ongkir-header {
                padding: 3rem 1.5rem;
                text-align : mid;
            }
        </style>**
    
    c. <style>
            .ongkir-header {
                padding: 3rem 1.5rem;
                text-align : round;
            }
        </style>**

    d. <style>
            .ongkir-header {
                padding: 3rem 1.5rem;
                text-align : top;
            }
        </style>**
```
16. Dimanakah letak pemanggilan class Ongkir-header yang benar untuk class yang telah dibuat...

``` 
    a. <div>
        <h1 class="ongkir-header">CodeOngkir</h1>
        <p class="lead">
            Project Cek Ongkir ke Seluruh Koda dan Kabupaten di Indonesia
        </p>
    </div>

    b. <div class="ongkir-header">
        <h1>CodeOngkir</h1>
        <p class="ongkir-header">
            Project Cek Ongkir ke Seluruh Koda dan Kabupaten di Indonesia
        </p>
    </div>

    c. <div>
        <h1>CodeOngkir</h1>
        <p class="lead">
            <class="ongkir-header"> Project Cek Ongkir ke Seluruh Koda dan Kabupaten di Indonesia
        </p>
    </div>

    **d. <div class="ongkir-header">
        <h1>CodeOngkir</h1>
        <p class="lead">
            Project Cek Ongkir ke Seluruh Koda dan Kabupaten di Indonesia
        </p>
    </div>**
```

17. Mengapa kita menggunakan CDN Font Awesome...
    
    a. Untuk menggunakan icon yang sebelumnya sudah di download 

    **b. Agar tidak perlu mendownload terlebih dahulu untuk menggunakan librari dan digunakan secara terhubung dengan internet**

    c. Agar tidak perlu mendownload terlebih dahulu untuk menggunakan librari dan digunakan tidak secara terhubung dengan internet

    d. Berfungsi untuk memberi efek rata tengah pada baris text

18. Bagaimana penulisan kode yang benar untuk memanggil CDN Font Awesome...
    
    **a. <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/js/all.min.js"></script>**
    
    b. <script img src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/js/all.min.js"></script>

    c. <script get="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/js/all.min.js"></script>

    d. <script put="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/js/all.min.js"></script>

## Membuat Fungsi Dependent Dropdown

19. Apa fungsi pluck di getProvince()...
    
    **a. Untuk mendapatkan title dan code pada tabel provinsi**

    b. Untuk mendapatkan semua isi dari tabel provinsi

    c. Untuk menghapus semua isi pada tabel provinsi

    d. Untuk hanya mendapatkan title saja dari tabel provinsi

20. Berikut yang manakah cara pemanggilan getProvince yang benar pada function index();...

    a. $province = getProvince();

    b. $this->province = getProvince();

    c. $getProvince = Province();

    **d. $province = $this->getProvince();**

21. Mengapa kita menggunakan compact pada fungsi index()...

    **a. Berfungsi untuk melakukan passing data dari controller ke view**

    b. Berfungsi untuk memanggil data dari tabel

    c. Untuk menghapus data yang ada di tabel

    d. Untuk menampilkan seluruh data yang terhubung dengan tabel provinsi

22. Dibawah ini manakah cara untuk menampilkan data provinsi pada view...
```
    **a. @foreach ($province as $key => $value )
            <option value= "{{ $key }}">{{ $value }}</option>
        @endforeach**

    b. @foreach ($province as $key => $value )
            <option value= "{{ $province }}">{{ $value }}</option>
        @endforeach

    c. @foreach ($province as $key => $value )
            <option value= "{{ $value }}">{{ $value }}</option>
        @endforeach

    d. @foreach ($province as $key => $value )
            <option value= "{{ $value }}">{{ $key }}</option>
        @endforeach
```
23. Dibawah ini Type yang manakah digunakan untuk mendapatkan data provinsi...

    a. Type: "PUT"

    b. Type: "DELETE"

    **c. Type: "GET"**

    d. Type: "POST"

24. Di mana letak kita untuk membuat tabel untuk database pada laravel...

    a.	Middleware
    
    b.	Controller
    
    c.	Routes
    
    **d. Migration**

## Cara Menggunakan Laravel Mix

25. Apa itu Laravel Mix...
    
    a. Laravel Mix adalah librari yang digunakan untuk menampilkan icon

    b. Laravel Mix adalah sebuah package untuk menjalankan npm

    **c. Laravel Mix adalah package frontend yang disiapkan untuk manajemen asset di laravel**

    d. Laravel Mix adalah package backend yang disiapkan untuk manajemen asset di laravel

26. Dimanakah hasil dari compile JQuery dan VueJs yang di Install atau sudah terinstall...

    **a. Public\js\app.js**

    b. Public\app.js

    c. Js\app.js

    d. App\app.js

27. Perintah npm install berguna untuk...
    
    a. Untuk menghasilkan file model baru

    b. Untuk menghasilkan file controller baru

    **c. Untuk menginstall seluruh dependency package yang ada di file package.json**

    d. Untuk menginstall Laravel Mix

28. Mengapa kita harus menginstall Node Js terlebih dahulu...

    **a. Untuk menginstall Dependency Package yang tidak tersedia oleh laravel secara bawaan**

    b. Untuk menginstall Package yang tersedia oleh laravel secara bawaan

    c. Untuk menginstall librari baru

    d. Untuk mengcompile Package yang tersedia oleh laravel secara bawaan

29. Kapan npm run prod digunakan...

    **a. Saat aplikasi sudah dalam tahap produksi atau publish**

    b. Saat aplikasi sedang dalam tahap development

    c. Saat aplikasi sedang dalam tahap menentukan kebutuhan fungsional

    d. Saat aplikasi dalam tahap persiapan

30. Dimanakah letak menaruh file web.php

    a.	Middleware
    
    b.	Controller
    
    **c.Routes**
    
    d.	Migration 

## Menginstall Libary Select2 dengan NPM dan Laravel Mix

31. NPM adalah...
    
    **a. Node Package Manager**

    b. New Package Manager

    c. Now Package Manager

    d. Network Package Manager

32. Perintah untuk install Npm Select2...
    
    a. npm install select2

    **b. npm i select2**

    c. install select2

    d. npm select2

33. Dimanakah letak untuk menaruh require('select2')...

    a. App.js

    **b. Bootstrap.js**

    c. Ongkir.js

    d. Components.js

34. Berikut penulisan kode yang benar untuk import select2

    a. import select2;

    **b. @import 'select2';**

    c. @import file 'select2';

    d. @import here 'select2';

35. Perintah untuk compile select2 yang akan diimport...
    
    a. Npm run prod

    b. Npm run prepare
    
    **c. Npm run dev**

    d. Npm run build

36. Perintah artisan untuk menjalankan local development server dalam laravel...

    a.	php artisan migrate
    
    b.	php artisan down
    
    **c. php artisan serve**
    
    d.	php artisan tinker

## Implementasi Select2 untuk Pencarian Realtime

37. Cara mengurutkan Kota dari atas kebawah...
    
    a. Asci

    b. Asec

    c. Desc

    **d. Asc**

38. Berikut penulisan kode yang benar untuk selector berdasarkan kota destinasi...
    
 ```   
    a.  $('#destination').select2({
        ajax: {
            url: '/api/cities',
            type: "POST",
            dataType: 'JSON',
            delay: 150,
            data: function (params) {
                return {
                    _token: $('meta[name="csrf-token"]').attr('content'),
                    search: $.trim(params.term)
                }
            },
            processResults: function (response) {
                return {
                    results: response
                }
            },
                cache: true
            }
        });

    **b.  $('#destination_city').select2({
        ajax: {
            url: '/api/cities',
            type: "POST",
            dataType: 'JSON',
            delay: 150,
            data: function (params) {
                return {
                    _token: $('meta[name="csrf-token"]').attr('content'),
                    search: $.trim(params.term)
                }
            },
            processResults: function (response) {
                return {
                    results: response
                }
            },
                cache: true
            }
        });**
    
    c. $('#destination_city').select2({
        ajax: {
            url: '/api/kota',
            type: "POST",
            dataType: 'JSON',
            delay: 150,
            data: function (params) {
                return {
                    _token: $('meta[name="csrf-token"]').attr('content'),
                    search: $.trim(params.term)
                }
            },
            processResults: function (response) {
                return {
                    results: response
                }
            },
                cache: true
            }
        });
    
    d.  $('#destination_city').select2({
        ajax: {
            url: '/api/city',
            type: "POST",
            dataType: 'JSON',
            delay: 150,
            data: function (params) {
                return {
                    _token: $('meta[name="csrf-token"]').attr('content'),
                    search: $.trim(params.term)
                }
            },
            processResults: function (response) {
                return {
                    results: response
                }
            },
                cache: true
            }
        });
```

39. Di dalam funtion SearchCities didalam parameter Where terdapat Like, fungsi tersebut digunakan untuk...
    
    **a. Untuk pencarian data yang sesuai atau mirip apa yang dicari**

    b. Untuk menampilkan data terbaru

    c. Untuk mencari data yang tidak sesuai dengan yang dicari

    d. Untuk mencari data yang baru dimasukan

40. Json_encode digunakan untuk...

    a. Menghapus nilai Json

    b. Mengubah nilai Json

    c. Mengirimkan nilai Json

    **d. Mengembalikan representasi JSON dari suatu nilai**

41. Cara mengaktifkan Cache yang benar untuk pemanggilan data yang sama agar lebih ringan adalah...

    a. Cache -> true;

    **b. Cache: true;**

    c. Cache: false;

    d. Cache = true;

42. Apa fungsi dari app key yang terdapat pada laravel...

    a.	Membuat aplikasi menjadi lebih keren
    
    **b. Memberikan keamanan bagi aplikasi**
    
    c.	Membuat aplikasi mudah diretas
    
    d.	Membuat aplikasi menjadi lebih berat

## Menampilkan Data Courier dan Aktifkan Form

43. Dibawah ini cara penulisan eloquent yang benar untuk menampilkan seluruh data kurir...

    **a. public function getCourier()
        {
            return Courier::all();
        }**

    b. public function getCourier()
        {
            return Courier::pluck();
        }
    
    c. public function getCourier()
        {
            return Courier::first();
        }
    
    d.public function getCourier()
        {
            return Courier::get();
        }

44. Jika kita tidak menaruh variabel courier di compact apa yang akan terjadi pada view...
    
    **a. Data kurir tidak tampil di view**

    b. Menampilkan data kurir di view

    c. Menampilkan data kurir berdasarkan tanggal dibuat

    d. Semua salah

45. Penulisan kode yang benar untuk store adalah...
    
    a. Route::push('/store', 'HomeController@store')->name('store');

    b. Route::put('/store', 'HomeController@store')->name('store');

    **c. Route::post('/store', 'HomeController@store')->name('store');**

    d. Route::get('/store', 'HomeController@store')->name('store');

46. Apa tujuan dari attribute name...
    
    a. Atribut name mengidentifikasi nilai input jika dikirim ke server melalui formulir PUT

    b. Atribut name mengidentifikasi nilai input jika dikirim ke server melalui formulir UPDATE

    **c. Atribut name mengidentifikasi nilai input jika dikirim ke server melalui formulir GET atau POST**

    d. Semua salah

47. Function store() digunakan untuk...

    a. Untuk menampilkan data

    b. Untuk mengubah data

    c. untuk mendapatkan data
    
    **d. Untuk insert data**

48. folder yang digunakan untuk melakukan konfigurasi pada laravel...

    **a. config**
    
    b.	controller
    
    c.	route
    
    d.	public

## Menginstall Package Rajaongkir

49. Dibawah ini penulisan perintah untuk menginstall package dari Rajaongkir...

    **a. Composer require kavist/rajaongkir:^1.1**

    b. Composer kavist/rajaongkir:^1.1

    c. Require kavist/rajaongkir:^1.1

    d. Download kavist/rajaongkir:^1.1
50. Dimana kita menaruh Api key dari Rajaongkir...

    a. Resource\Api
    
    b. App\Api

    **c. .env**

    d. Public\js

51. Penulisan kode yang benar berisi Api Key Rajaongkir adalah...

    a. RAJAONGKIR=isi_API_key_Anda_disini

    **b. RAJAONGKIR_API_KEY=isi_API_key_Anda_disini**

    c. RAJAONGKIR_API=isi_API_key_Anda_disini

    d. RAJAONGKIR_KEY_API=isi_API_key_Anda_disini

52. Dimanakah kita mendapatkan Api Key Rajaongir...

    **a. Halaman RajaOngkir**

    b. Menjalankan perintah composer require api key = rajaongkir

    c. Sudah tergenerate oleh laravel

    d. Semua salah
   
53. Bagaimana cara untuk mendapatkan data provinsi berdasarkan id...
    
    a. $daftarProvinsi = RajaOngkir::provinsi()->put(int|string $id)

    b. $daftarProvinsi = RajaOngkir::provinsi()->get(int|string $id)

    **c. $daftarProvinsi = RajaOngkir::provinsi()->find(int|string $id)**

    d. $daftarProvinsi = RajaOngkir::provinsi()->post(int|string $id)

54. Cara untuk mengambil data pada route adalah...

    a.	post
    
    **b. get**
    
    c.	put
    
    d.	delete

## Menampilkan Data Ongkir

55. Cara mendapatkan data hanya satu objek kota...
    
    **a. City::where('code', $code)->first();**

    b. City::where('code', $code)->get();

    c. City::put('code', $code)->first();

    d. City::get('code', $code)->first();

56. Redirect()->back() digunakan untuk...

    a. Menuju halaman daftar kurir

    b. Menuju halaman kota

    **c. Mengembalikan ke halaman semula**

    d. Semua salah

57. Apa fungsi dari @extends('layouts.app')...

    **a. Penanda bahwa kita menggunakan layouts.app sebagai tampilan website**

    b. Penanda bahwa kita menggunakan layouts.app sebagai backend

    c. Digunakan untuk menampilkan halaman daftar kurir

    d. Penanda bahwa kita menggunakan layouts.app sebagai tampilan daftar kota

58. Pada Rajaongkir terdapat Etd, Etd adalah...
    
    a. Estimated Tour of Departure

    b. Estimated Time off Departure

    c. Estimated Time of Depot

    **d. Estimated Time of Departure**

59. Array adalah...
    
    a. Array adalah tipe data tidak terstruktur yang berfungsi untuk menyimpan satu data saja

    b. Array adalah tipe data terstruktur yang berfungsi untuk menyimpan satu data saja

    c. Array adalah tipe data terstruktur yang berfungsi untuk menyimpan sejumlah data yang tipenya berbeda

     **d. Array adalah tipe data terstruktur yang berfungsi untuk menyimpan sejumlah data yang tipenya sama**

60. Fungsi dari class request pada controller laravel adalah...

    a.	Menggantikan fungsi controller
    
    **b. Menggantikan fungsi global GET dan POST**
    
    c.	Membuat web menjadi cepat
    
    d.	Semua salah      




