# Smiling Story API


## Base URL
https://smiling-back-end-wdb.vercel.app

## Endpoints

### Get List of Story

> Mendapatkan daftar cerita

- URL: `/list` 
- method: `GET`
- example: `https://smiling-back-end-wdb.vercel.app/list`
- response: 
``` json
{
    "stories": [
        {
            "id": "1",
            "title": "Bagaimana Zebra Mendapatkan Belangnya",
            "thumbnailId": "1",
            "musicId": "3",
            "musicInfo": "Escape Velocity by Scott Buckley",
            "illustrator": "Stephen Wallace",
            "writer": "Jaco Jacobs",
            "translator": "Yustin S",
            "publisher": "Pratham Books",
            "originalURL": "https://storyweaver.org.in/stories/131661-how-zebra-got-his-stripes",
            "copyright": "CC-BY-4.0",
            "description": "Zebra sang penyelamat yang berani",
            "content": [
                {
                    "pictureId": "1",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/28310-a-warm-day",
                    "story": "Jaman dahulu kala, saat kulit Zebra masih berwarna putih, terjadi kemarau panjang. Berbulan-bulan tidak ada air hujan setetespun. Rumput menjadi tandus, pohon-pohon menjadi gundul dan satu demi satu sungai mengering. Antelop, Babi Hutan dan Zebra harus berjalan sangat jauh setiap hari untuk mencari air. Suatu pagi saat Antelop sampai di sebuah lubang berisi air, dia mendengar suara yang yang terdengar marah, \"Pergi! Cepat lari! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon!\" Mata Antelop terbelalak kaget. Babon duduk diatas batu disamping lubang air sedang membakar pisang dengan api terbuka. \"Tapi aku sangat haus, lidahku terasa seperti daging kering.\" kata Antelop. \"Dimana aku akan menemukan air?\" Babon menggeram. \"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Antelop melihat gigi Babon yang panjang dan menakutkan. Dia berbalik dan berlari menjauh."
                },
                {
                    "pictureId": "2",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/28312-chased-by-chimpanzee",
                    "story": "Beberapa saat kemudian Babi hutan mendatangi lubang air yang sama. Tapi, segera setelah dia menundukkan kepalanya untuk meminum air terdengar bunyi marah, \"Pergi!Cepat lari! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon!\" Terkejut, Babi Hutan segera berbalik. Dia melihat Babon diatas batu disamping lubang air sedang membakar pisang. \"Tapi aku sangat haus, rasanya seperti memakan debu,\" kata Babi Hutan. \"Dimana aku akan menemukan air?\" Babi Hutan menggerutu. \"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Sesaat, Babi Hutan siap melawan, tapi dia menjadi takut saat melihat gigi Babon yang panjang. Dia berbali dan berlari menjauh dengan cepat."
                },
                {
                    "pictureId": "3",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/28314-the-white-horse-and-the-chimpanzee",
                    "story": "Beberapa saat kemudian Zebra muncul dilubang air. Sebelum dia sempat meminum air,dia mendengar suara marah. \"Pergi!Cepatlari! Atau kau akan merasakan akibatnya! Inilubang air milik Babon!\" Zebra mendengusdan mendongak ke atas. Dia melihat Babonsedang duduk diatas batu membakar pisang."
                },
                {
                    "pictureId": "4",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/28315-horse-attacks-chimpanzee",
                    "story": "\"Tapi aku sangat haus, rasanya seperti lidahku berada diluar mulutku semalam.\" kata Zebra. \"Dimana aku bisa menemukan air?\"\"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Babon menunjukkan gigi panjangnya, Zebra tidak takut. Dengan kuku kakinya yang berderap, dia menyerang Babon. Zebra sangat marah dan berlari menerobos api bakar milik Babon. Percikan api, asap dan pisang beterbangan. Babon mencoba melarikan diri, tapi terlambat. Zebra menendangnya dengan keras sampai Babon terlempar di udara. \"Aduh!\" teriak matahari. Batu itu sangat panas sampai membakar rambut di pantatnya."
                },
                {
                    "pictureId": "5",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/28317-the-animals-and-black-striped-horse-meet",
                    "story": "Dan kulit Zebra tidak lagi berwarna putih. Api bakar Babon membakar kulitnya menjadi belang bergaris. Sekarang semua hewan bisa minum dengan aman di lubang air. Dan setiap pagi saat mereka datang untuk minum, Antelop, Babi Hutan dan Zebra bernyanyi, \"Ayo kita minum selagi jalan-jalan, ini lubang air bersama!\""
                }
            ]
        },
        {
            "id": "2",
            "title": "Berapa Berat Udara?",
            "thumbnailId": "2",
            "musicId": "2",
            "musicInfo": "Lullaby by Keys of Moon",
            "illustrator": "Shohei Emura",
            "writer": "Yasaswini Sampathkumar",
            "translator": "Muhammad Dirgantara Esa Valentino Am",
            "publisher": "Pratham Books",
            "originalURL": "https://storyweaver.org.in/stories/360284-berapa-berat-udara",
            "copyright": "CC-BY-4.0",
            "description": "Lakshmi dan teman sekelasnya mencari tahu apakah udara memiliki berat",
            "content": [
                {
                    "pictureId": "1",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/14153-girl-and-shopping-bags",
                    "story": "Telapak tangan Lakshmi kebas karena menjinjing kantong plastik yang berat. Kantong pertama berisi setengah kilogram kentang. Kantong kedua berisi setengah kilogram tomat dan sepotong labu abu. Lakshmi masih harus berjalan setengah kilometer sebelum sampai ke rumah. Ia beristirahat dan meletakkan bawaannya di depan sebuah toko. Seorang penjual balon melintas. \"Baloooon, baloooon warna-warni!\" Betapa ringan tampaknya balon sebanyak itu. Seandainya saja kantong-kantong bawaan Lakshmi hanya berisi udara! Tiba-tiba ia teringat sebuah momen di kelas IPA. Ibu Guru Ammu berkata udara mempunyai berat. \"Satu meter kubik * udara beratnya sama dengan 1.2 kilogram.\" *1 meter kubik adalah volume sebuah kubus berukuran 100 cm x 100 cm x 100 cm. Terdengar berat sekali - hampir sama beratnya dengan kantong bawaan Laksmi. Namun, seandainya udara memiliki berat, bukankah seharusnya Lakshmi bisa merasakannya?"
                },
                {
                    "pictureId": "2",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/16423-a-girl-building-with-wood-with-her-sister-watching",
                    "story": "Saat tiba di rumah, Lakshmi memutuskan untuk menemukan jawabannya. Gowri, adik perempuannya, bisa ikut membantu. Lakshmi mengambil dua belas batang lidi dari sapu baru di dekat tempat cuci piring di dapur. Dengan menggunakan penggaris, ia memastikan setiap lidi panjangnya 100 cm. Lalu ia menempelkan satu lidi dengan lidi yang lain sehingga membentuk kerangka kubus. Lakshmi dan Gowri kemudian membungkus setiap sisinya dengan surat kabar bekas. \"Nah, udara di dalam seharusnya sudah seberat 1.2 kilogram!\" pikir Laksmi. Ia lalu berbaring telentang dengan kubus itu di dadanya agar ia bisa merasakan beratnya. Ia tidak merasakan apa- apa! Namun, ketika Gowri menggantinya dengan kantong sayuran, ia dapat merasakan beban di dadanya. Karena masih penasaran, selanjutnya Lakshmi meniup sebuah balon dan menjatuhkannya. Bila memang udara memiliki berat, balon yang sudah ditiup tentu akan jatuh lebih cepat dibanding balon kosong, bukan? Nyatanya, balon yang ditiup Lakshmi malah melayang jauh. Ia sampai harus mengejarnya. Lakshmi membawa balon itu ke Puskesmas. Di ruang dokter, sementara adiknya sedang divaksin, Lakshmi berdiri di timbangan--berat badannya 19 kilogram. Ia kemudian meletakkan balon itu di atas timbangan secara perlahan. Ternyata, jarum timbangan sama sekali tidak bergerak."
                },
                {
                    "pictureId": "3",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/14160-girl-asking-a-question-in-class",
                    "story": "\"Bu Guru, udara tidak memiliki berat,\" kata Lakshmi mengemukakan hasil temuannya di sekolah keesokan harinya. \"Udara tidak bisa dirasakan.\" \"Bisa. Saat udara bergerak kita bisa merasakannya,\" kata ibu guru sambil meniup sehelai rambut di keningnya. Ia juga menunjuk ke arah jendela. Tampak dedaunan bergoyang dan awan mendung bergerak. \"Udara juga dapat menggerakkan berbagai macam benda.\" \"Apakah udara memiliki berat?\" tanya Ibu Ammu. \"Ayo kita cari tahu sama-sama hari ini.\" Ia lalu menulis sebuah pesan dan menyerahkannya kepada salah seorang murid. \"Shyam, tolong ambilkan tiga pak balon tebal untuk Ibu. Yang lain ayo bantu Ibu, kita bereskan ruang kelas untuk percobaan kita.\" Mereka lalu menggeser kursi dan meja ke sudut dan membuat ruang kosong di tengah. Ibu Ammu lalu mengambil kotak kardus. Ia mengukur sisi kotak itu dan berkata, \"Kotak ini volumenya kira- kira satu meter kubik. Sekarang ayo tiup balon-balon ini dan masukkan ke dalam kotak.\""
                },
                {
                    "pictureId": "4",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/14164-students-putting-balloon-in-a-box",
                    "story": "Selama setengah jam, murid-murid meniup balon hingga wajah mereka memerah. Mereka mengikat ujung setiap balon yang berhasil ditiup. Tidak semua balon berakhir di kardus. Beberapa balon melayang jauh. Ada pula yang pelan-pelan mengempis. BANG! Ada juga yang meletus. Ibu Ammu berdiri di dekat kardus dan mengamati para siswa yang mengisinya dengan balon. Setelah kardus itu penuh, Ibu Ammu menyatukan semua balon dengan tali menjadi bola balon raksasa. Para murid lalu beramai-ramai membawa bola balon itu ke kantor Kepala Sekolah untuk ditimbang."
                },
                {
                    "pictureId": "5",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/17562-a-girl-holding-balloons-a-woman-bursting-them",
                    "story": "Lakshmi berdiri di timbangan--beratnya masih tetap 19 kilogram. Ibu Ammu menyerahkan bola balon kepadanya. Sambil Lakshmi bersusah payah memegang bola raksasa itu, murid yang lain memperhatikan dengan saksama angka di timbangan. Apakah jarumnya bergerak? Betul, jarum timbangan melewati angka 19 kilogram.* *Berat udara bisa bervariasi tergantung lokasi. **Karet balon juga memiliki berat. ***Mengapa jarumnya bergerak hanya sedikit saja? Apakah ini ada hubungannya dengan tekanan udara di luar balon? Ibu Ammu kemudian mengambil peniti dan menusuk lima balon. Lakshmi tersentak, tetapi kemudian tertawa. Murid lain bersorak saat Ibu Ammu meletuskan sisanya. Ketika balon terakhir meletus, jarum timbangan kembali menunjukkan 19 kilogram."
                },
                {
                    "pictureId": "6",
                    "pictureAttr": "https://storyweaver.org.in/illustrations/14169-girl-raising-her-hand",
                    "story": "Lakshmi merasa senang. Hari itu di sekolah sudah terbukti udara memiliki berat. Namun,sebelum lonceng berbunyi, Lakshmi masih punya satu pertanyaan: “Bu, bila udara mempunyai berat, mengapa balon melayang saat terisi udara dan terjatuh saat meletus?” Menurutmu mengapa? Tahukah kamu, molekul udara di sekitar kita lebih banyak jumlahnya dibanding butiran pasir yang ada di semua pantai di Bumi? Bila bertubrukan dengan kita, partikel udara menekan tubuh kita."
                }
            ]
        }
    ]
}  
```


### Get Detail of Story

> Mendapatkan detail cerita

- URL: `/detail/{id}` 
- method: `GET`
- example: `https://smiling-back-end-wdb.vercel.app/detail/1`
- response: 
``` json
{
    "id": "1",
    "title": "Bagaimana Zebra Mendapatkan Belangnya",
    "thumbnailId": "1",
    "musicId": "3",
    "musicInfo": "Escape Velocity by Scott Buckley",
    "illustrator": "Stephen Wallace",
    "writer": "Jaco Jacobs",
    "translator": "Yustin S",
    "publisher": "Pratham Books",
    "originalURL": "https://storyweaver.org.in/stories/131661-how-zebra-got-his-stripes",
    "copyright": "CC-BY-4.0",
    "description": "Zebra sang penyelamat yang berani",
    "content": [
        {
            "pictureId": "1",
            "pictureAttr": "https://storyweaver.org.in/illustrations/28310-a-warm-day",
            "story": "Jaman dahulu kala, saat kulit Zebra masih berwarna putih, terjadi kemarau panjang. Berbulan-bulan tidak ada air hujan setetespun. Rumput menjadi tandus, pohon-pohon menjadi gundul dan satu demi satu sungai mengering. Antelop, Babi Hutan dan Zebra harus berjalan sangat jauh setiap hari untuk mencari air. Suatu pagi saat Antelop sampai di sebuah lubang berisi air, dia mendengar suara yang yang terdengar marah, \"Pergi! Cepat lari! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon!\" Mata Antelop terbelalak kaget. Babon duduk diatas batu disamping lubang air sedang membakar pisang dengan api terbuka. \"Tapi aku sangat haus, lidahku terasa seperti daging kering.\" kata Antelop. \"Dimana aku akan menemukan air?\" Babon menggeram. \"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Antelop melihat gigi Babon yang panjang dan menakutkan. Dia berbalik dan berlari menjauh."
        },
        {
            "pictureId": "2",
            "pictureAttr": "https://storyweaver.org.in/illustrations/28312-chased-by-chimpanzee",
            "story": "Beberapa saat kemudian Babi hutan mendatangi lubang air yang sama. Tapi, segera setelah dia menundukkan kepalanya untuk meminum air terdengar bunyi marah, \"Pergi!Cepat lari! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon!\" Terkejut, Babi Hutan segera berbalik. Dia melihat Babon diatas batu disamping lubang air sedang membakar pisang. \"Tapi aku sangat haus, rasanya seperti memakan debu,\" kata Babi Hutan. \"Dimana aku akan menemukan air?\" Babi Hutan menggerutu. \"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Sesaat, Babi Hutan siap melawan, tapi dia menjadi takut saat melihat gigi Babon yang panjang. Dia berbali dan berlari menjauh dengan cepat."
        },
        {
            "pictureId": "3",
            "pictureAttr": "https://storyweaver.org.in/illustrations/28314-the-white-horse-and-the-chimpanzee",
            "story": "Beberapa saat kemudian Zebra muncul dilubang air. Sebelum dia sempat meminum air,dia mendengar suara marah. \"Pergi!Cepatlari! Atau kau akan merasakan akibatnya! Inilubang air milik Babon!\" Zebra mendengusdan mendongak ke atas. Dia melihat Babonsedang duduk diatas batu membakar pisang."
        },
        {
            "pictureId": "4",
            "pictureAttr": "https://storyweaver.org.in/illustrations/28315-horse-attacks-chimpanzee",
            "story": "\"Tapi aku sangat haus, rasanya seperti lidahku berada diluar mulutku semalam.\" kata Zebra. \"Dimana aku bisa menemukan air?\"\"Bukan urusanku! Cepat pergi! Atau kau akan merasakan akibatnya! Ini lubang air milik Babon.\" Babon menunjukkan gigi panjangnya, Zebra tidak takut. Dengan kuku kakinya yang berderap, dia menyerang Babon. Zebra sangat marah dan berlari menerobos api bakar milik Babon. Percikan api, asap dan pisang beterbangan. Babon mencoba melarikan diri, tapi terlambat. Zebra menendangnya dengan keras sampai Babon terlempar di udara. \"Aduh!\" teriak matahari. Batu itu sangat panas sampai membakar rambut di pantatnya."
        },
        {
            "pictureId": "5",
            "pictureAttr": "https://storyweaver.org.in/illustrations/28317-the-animals-and-black-striped-horse-meet",
            "story": "Dan kulit Zebra tidak lagi berwarna putih. Api bakar Babon membakar kulitnya menjadi belang bergaris. Sekarang semua hewan bisa minum dengan aman di lubang air. Dan setiap pagi saat mereka datang untuk minum, Antelop, Babi Hutan dan Zebra bernyanyi, \"Ayo kita minum selagi jalan-jalan, ini lubang air bersama!\""
        }
    ]
}
```


### Search Story

> Mencari Cerita dengan Keyword

- URL: `/story/search?title={keyword}`
- method: `GET`
- example: `https://smiling-back-end-wdb.vercel.app/story/search?title=adil`
- response: 
``` json
[
    {
        "id": "3",
        "title": "Berbagi dengan Adil",
        "thumbnailId": "3",
        "musicId": "1",
        "musicInfo": "Positive Ukulele by Sokolovsky Music",
        "illustrator": "Magriet Brink",
        "writer": "Hamsa Venkatakrishnan, Penelope Smith",
        "translator": "Franciscus Dondy",
        "publisher": "Pratham Books",
        "originalURL": "https://storyweaver.org.in/stories/337835-sharing-equally",
        "copyright": "CC-BY-4.0",
        "description": "Sebuah cerita tentang matematika dan kue untuk belajar membagi dengan adil meskipun hal itu rumit",
        "content": [
            {
                "pictureId": "1",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22366-three-kids-working-on-a-garden",
                "story": "Sabtu pagi ini cuaca panas terik di peternakan. Maya, Duksi, dan Dubi membantu Mama K di kebunnya. Anak- anak berkegiatan sepanjang hari. Mereka memupuk tanaman di tanah dengan kompos, menyiangi rumput liar, dan menyirami tanaman. Mereka memanen buah-buahan dan sayur- sayuran yang sudah matang. Hari ini mereka mendapatkan panen stroberi, bayam, dan wortel yang segar. Mama K selalu menawarkan berbagai macam suguhan kepada anak-anak sebagai ucapan terima kasih atas bantuan mereka. Kue, coklat, permen berbentuk ular, dan juga apel, pir, atau jeruk. Mama K hanya punya satu aturan, \"Berbagilah dengan adil!\" Anak-anak menjadi paham bahwa mereka harus membagi berbagai macam kudapan dengan adil, sehingga masing-masing mendapatkan bagian yang sama. Hari ini Mama K membua kue tart stroberi yang dioles dengan lapisan gula warna merah muda dan dihiasi dengan sejenis buah buni dari kebunnya. Anak-anak menunggu kudapan sambil duduk di rerumputan. \"Ini dia!\" kata Mama K sambil tersenyum, \"tapi jangan lupa aturannya, masing-masing harus mendapat bagian yang sama. Berbagilah dengan adil. Dan jangan bertengkar!\""
            },
            {
                "pictureId": "2",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22370-kids-looking-at-the-cake",
                "story": "Maya-lah yang mulai membagi kue itu. Dia menggaris lapisan gula dengan pisaunya sedangkan yang lain memperhatikannya. Dia belum mulai memotong kue itu. Dia menunggu teman-temannya memberitahunya apakah garis yang dibuatnya sudah benar. \"Sepertinya, aku akan memotong kuenya di dua tempat,\" kata Maya, \"di sini dan di sana, dengan begitu kita akan mendapatkan tiga potong kue yang sama.\" \"Asal bicara,\" seru Duksi, \"bagian tengah terlalu besar!\" Maya mengangkat bahunya sambil tertawa. Kemudian, dia meminta Duksi untuk mencoba memotong kue itu."
            },
            {
                "pictureId": "3",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22372-kids-dividing-up-the-cake",
                "story": "\"Berikan pisaunya kepadaku. Aku akan memotongnya. Ini sangat mudah!\" teriak Duksi. Dia menghapus garis yang Maya buat di atas lapisan gula dan menjilat jemarinya. Dia menggambar garis di tengah kue, kemudian membuat garis lain di sampingnya. \"Lihatlah, ini tiga bagianku!\" \"Tapi itu tidak adil!\" Maya dan Dubi memprotes. \"Bagilah dengan cara yang adil.\" kata Dubi, \"bagian-bagian itu harus berukuran dan berbentuk sama.\" \"Mengapa kamu tidak mencobanya, Einstein?\" celetuk Duksi sambil tertawa. \"Kami bertaruh bahwa kamu tidak akan bisa!\""
            },
            {
                "pictureId": "4",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22377-kids-successfully-divide-cake",
                "story": "\"Aku lebih memilih jika kue ini berbentuk kotak atau persegi, itu akan lebih mudah!\" Dubi menghela nafas. \"Akan lebih mudah juga untuk berbagi kue bundar ini jika kita berempat.\" sambung Maya. Tiba-tiba sebuah gambar muncul di kepala Dubi. Gambar itu berbentuk lambang perak yang menempel di depan truk merah milik ayahnya. Setiap hari minggu, Dubi membantu ayahnya mencuci truk merah dan mengelap lambang itu sampai mengkilap. \"Eureka! Aku menemukannya!\" teriak Dubi. \"Ah, Dubi, kamu selalu mengejutkan kami.\" bisik Duksi. \"Sudahkah kamu tahu apa yang akan kaulakukan?\" tanya Maya. Dubi tersenyum. Untuk sementara, dia memilih menyimpannya untuk diri sendiri. Rahasia. Dia akan menceritakan hal itu nanti kepada ayahnya. Dia menggunakan pisau untuk menghapus garis yang dibuat Duksi. Kemudian ia menggambar tiga garis di atas lapisan gula. Garis itu terlihat seperti lambang truk ayahnya yang membagi kue menjadi tiga bagian yang sama."
            },
            {
                "pictureId": "5",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22378-mother-serves-juice",
                "story": "Mama K bergabung dengan mereka dengan membawa tiga gelas jus stroberi di atas nampan. \"Lihat, Mama K, Dubi telah menemukan cara memotong kue menjadi tiga bagian yang sama.\" Maya menjelaskan. \"Tiga bagian yang sama? Bagus sekali Dubi!\" teriak Mama K. \"Kalian berhasil membagi kue dengan adil. Mama bangga dengan kalian. Sekarang, potonglah kue itu dan minumlah jus stroberi ini. Kemudian waktunya untuk pulang. Mama akan memberikan piring untuk membawa pulang bagian kue kalian.\" Maya memotong kue mengikuti garis yang digambar Dubi yang membagi kue menjadi tiga bagian adil. Anak-anak menumpuk irisan-irisan kue di atas satu sama lain sambil tertawa untuk memastikan bahwa semua irisan sama rata."
            },
            {
                "pictureId": "6",
                "pictureAttr": "https://storyweaver.org.in/illustrations/22382-mother-kids-are-excited-to-see-his-father",
                "story": "Ayah Dubi datang menjemput anak-anak. Dia berlari menemui ayahnya, tidak sabar untuk segera bercerita bagaimana lambang truk ayahnya telah membantunya untuk memecahkan masalah yang pelik."
            }
        ]
    }
]
```


### Add Review

> Menambahkan Review pada Cerita

- URL: `/review`
- Method: `POST`
- Headers:
    - `Content-Type: application/json`
- Body:
    - JSON: `{"id": string, "name": string, "review": string}`


### Story Thumbnail Image

> Mendapatkan Thumbnail Cerita

- URL: `/thumbnail/{id}`


### Story Image

> Mendapatkan Image Cerita

- URL: `/images/{idS}/{id}`




