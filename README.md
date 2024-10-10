muhammadbaihaqi
Index HTML
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Adzanil Rachmadhi">
    <meta name="keyword" content="Belajar HTML, Belajar Web">
    <meta name="description" content="Praktikum modul 2">
    <meta name="robots" content="index, follow">

    <title>Pengenalan HTML Tingkat Lanjut</title>
</head>

<body>
    <strong>Praktikum Pemrograman Web</strong>
    <hr>

    <h1>Pengenalan HTML Tingkat Lanjut</h1>
    <hr>

    <div>
        <h2>Element Form</h2>
        <hr>
        <form action="" method="get">
            <p><input type="text" name="text_form" size="20"></p>
            <p><input type="text" name="text_form" size="20" placeholder="Dengan Placeholder"></p>
            <p><input type="text" name="readonly_form" size="20" value="Ini Readonly" readonly></p>
            <p><input type="text" name="disabled_form" value="Ini Disabled" size="20" disabled></p>
            <p><input type="text" name="required_form" size="20" required placeholder="Ini Required"></p>

            <p><input type="email" name="email_form" size="20" placeholder="Ini Email"></p>
            <p><input type="password" name="password_form" size="20" placeholder="Ini Password"></p>
            <p><input type="file" name="file"></p>
            <p><input type="hidden" name="hidden_form" value="123456"></p>

            <p>
                <textarea name="textarea_form" cols="30" rows="5" placeholder="Ini Textarea"></textarea>
            </p>

            <p>
                <select name="pilihan">
                    <option value=1>Pilihan 1</option>
                    <option value=2 selected>Pilihan 2</option>
                    <option value=3>Pilihan 3</option>
                    <option value=4>Pilihan 4</option>
                    <option value=5>Pilihan 5</option>
                </select>
            </p>

            <p>
                <input type="radio" name="radio" value="radio1" id="radio1" checked><label for="radio1">Radio 1</label>
                <input type="radio" name="radio" value="radio2" id="radio2"><label for="radio2">Radio 2</label>
            </p>

            <p>
                <input type="checkbox" name="checkbox1" value="checkbox1" id="checkbox1"><label
                    for="checkbox1">Checkbox 1</label>
                <input type="checkbox" name="checkbox2" value="checkbox2" id="checkbox2"><label
                    for="checkbox2">Checkbox 2</label>
            </p>

            <p>
                <input type="reset" value="Reset">
                <input type="submit" value="Simpan">
                <input type="button" value="Button" onclick="">
            </p>
        </form>
    </div>

    <div>
        <h2>Element Embed</h2>
        <hr>
        <embed src="assets/file.pdf" width="800" height="1000" type="application/pdf">
    </div>

    <div>
        <h2>Elemen Object</h2>
        <hr>
        <object data="assets/file.pdf" width="800" height="1000" type="application/pdf"></object>
    </div>

    <div>
        <h2>Element Iframe</h2>
        <hr>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/QIas1H7H_m0" title="YouTube video player"
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
    </div>

    <div>
        <h2>Element Semantic HTML5</h2>
        <hr>
        <header>Ini Header</header>
        <main>Ini Main</main>
        <section>Ini Section</section>
        <aside>Ini Aside</aside>
        <nav>Ini Nav</nav>
        <footer>Ini Footer</footer>
    </div>

    <br><br>
    <div>
        <hr>
        <strong>Program Studi Sistem Informasi ITTelkom Surabaya</strong>
    </div>
</body>
</html>

Semantic HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      table {
        border-spacing: 2;
        border-collapse: collapse;
        width: 100%;
      }

      th,
      td {
        border: solid 1px black;
        padding: 10px;
      }

      /* {
        background-color: lightsteelblue;
      } */

      tfoot {
        font-weight: bold;
      }
      .Body-text {
        text-align: center;
      }
      .nastedOneCategory {
        text-align: center;
      }
      .videoIframe {
        margin-top: 1rem;
      }
      .artikelLinks {
        vertical-align: top;
      }
      .artikelLinks div ul li {
        margin-top: 0.5rem;
      }
      .nastedBottom {
        vertical-align: top;
      }
    </style>
  </head>
  <body>
    <div>
      <table>
        <thead>
          <tr>
            <th>
              <img
                src="https://bis-sby.telkomuniversity.ac.id/wp-content/uploads/2024/03/LogoSiBaru.png"
                alt="logo"
                width="100px"
              />
            </th>
            <td>
              <table>
                <thead>
                  <tr>
                    <th>Tentang Kami</th>
                    <th>Akademik</th>
                    <th>Dosen & Staff</th>
                    <th>Kerja Sama</th>
                    <th>Blog</th>
                  </tr>
                </thead>
              </table>
            </td>
            <th>
              <a href="#">Admisi</a>
            </th>
          </tr>
        </thead>
      </table>
    </div>
    <div class="Body-text">
      <h2>Blog Sistem Informasi</h2>
    </div>
    <div>
      <table>
        <tr>
          <td>
            <table>
              <tr>
                <td width="75%">
                  <div>
                    <h3>
                      Dua Wisudawan Sistem Infromasi Berhasil Meraih Predikat
                      Cumlaude
                    </h3>
                  </div>
                  <div>
                    <p>
                      Institut Teknologi Telkom Surabaya telah menggelar prosesi
                      wisuda ke-1 secara luring di g hotel Grand Dafam, Surabaya
                      pada Sabtu (26/03/2022) kemarin. Prosesi wisuda ini
                      merupakan yang pertama dilakukan sejak kampus ini berdiri
                      di tahun 2018 lalu. Pada wisuda pertama ini, 16 wisudawan
                      telah dinyatakan lulus secara sah olch Rektor IT Telkom
                      Surabaya Bapak Dr. Tri Arief Sardjono, S.T., M.T.
                    </p>
                    <p>
                      Seluruh wisudawan merupakan mahasiswa yang berhasil lulus
                      dengan masa stadi 3,5 tahun. Dua diantaranya merupakan
                      mahasiswa program studi Sistem Informasi. Mereka adalah
                      Amalina alina Tri Setya Berliana din Irene Dyah Ayuwati.
                      Keduanya berhasil menyandang gelar S.Kom dengan predikat
                      cumlaude. Wisudawan dengan IPK tertinggi adalah Amalina
                      Tri S Berliana yang tidak lain merupakan mahasiswa program
                      studi Sistem Informasi dengan IPK 3.96. Setya
                    </p>
                    Pada prosesi wisuda ini pula, Rektor ITTelkom Surabaya telah
                    menyampaikan pesannya dengan penuh sukacita. Beliau berpesan
                    bagi seluruh wisudawan agar terus mengembankan diri sehingga
                    dapat mengambil peran di era transformasi digital yang
                    disruptif ini. Acara wisada ini dapat disaksikan melalui
                    kanal youtube ITTelkom Surabaya hanbok-Endksibo
                  </div>
                  <div class="videoIframe">
                    <iframe
                      width="560"
                      height="315"
                      src="https://www.youtube.com/embed/bboTVfT1NWY?si=sgAhpZXkGKGKlLdy"
                      title="YouTube video player"
                      frameborder="0"
                      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                      referrerpolicy="strict-origin-when-cross-origin"
                      allowfullscreen
                    ></iframe>
                  </div>
                </td>
                <td class="artikelLinks">
                  <div>
                    <h4>Tautan Penting</h4>
                    <ul>
                      <li>
                        <a href="#">Lorem, ipsum dolor.</a>
                      </li>
                      <li>
                        <a href="#"
                          >Lorem ipsum dolor sit amet consectetur adipisicing
                          elit.</a
                        >
                      </li>
                      <li>
                        <a href="#">Lorem ipsum dolor sit amet consectetur.</a>
                      </li>
                      <li>
                        <a href="#"
                          >Lorem ipsum dolor sit amet consectetur adipisicing
                          elit. Quisquam.</a
                        >
                      </li>
                      <li>
                        <a href="#"
                          >Lorem ipsum dolor sit amet consectetur adipisicing
                          elit. Quod?</a
                        >
                      </li>
                      <li>
                        <a href="#">Lorem ipsum dolor sit amet consectetur.</a>
                      </li>
                    </ul>
                  </div>
                  <div>
                    <h4>Artikel Terpopuler</h4>
                    <ul>
                      <li>
                        <a href="#"
                          >Lorem ipsum dolor sit amet consectetur adipisicing
                          elit. Quisquam.</a
                        >
                      </li>
                      <li>
                        <a href="#"
                          >Lorem ipsum dolor sit amet consectetur adipisicing
                          elit. Quod?</a
                        >
                      </li>
                      <li>
                        <a href="#">Lorem ipsum dolor sit amet consectetur.</a>
                      </li>
                    </ul>
                  </div>
                </td>
              </tr>
            </table>
          </td>
        </tr>
        <tr >
          <td>
            <table class="">
              <tr class="nastedBottom">
                <td>
                  <h4>Sistem informasi</h4>
                  <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                    Architecto debitis ipsam maxime minus ab magni illo aliquid
                    atque!
                  </p>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Accusamus, inventore esse!
                  </p>
                  <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                    Veritatis maxime est asperiores temporibus veniam tempora
                    atque quisquam.
                  </p>
                </td>
                <td>
                  <div>
                    <h4>Tautan Penting</h4>
                    <ul>
                      <li>Mahasiswa & Alumni</li>
                      <li>Kerja Sama</li>
                      <li>Proyek</li>
                    </ul>
                  </div>
                  <div>
                    <h4>Tautan Bermanfaat</h4>
                    <ul>
                      <li>Telkom Indonesia</li>
                      <li>Yayasan Pendidikan Telkom</li>
                      <li>ITTelkom Surabaya</li>
                      <li>Website SMB</li>
                    </ul>
                  </div>
                </td>
                <td>
                  <div>
                    <h4>Info Kontak</h4>
                    <ul>
                      <li>
                        <strong>Alamat :</strong> Lorem ipsum dolor sit amet
                        consectetur.
                      </li>
                      <li><strong>Telpone :</strong> 0937465890</li>
                      <li><strong>Email :</strong> Lorem ipsum@dolor sit</li>
                    </ul>
                  </div>
                  <div>
                    <h4>Media Sosial</h4>
                    <ul>
                      <li>Instagram</li>
                    </ul>
                  </div>
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </div>
    <div>
      <p><strong>Copyright © 2023 Telkom University</strong></p>
      <p>builded by CoderTeam</p>
    </div>
  </body>
<html>

Form HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Registrasi</title>
</head>
<body>
    <h1>Form Registrasi</h1>
    
    <form>
        <fieldset>
            <legend>Biodata</legend>
            <label for="nama">Nama Mahasiswa:</label>
            <input type="text" id="nama" name="nama" placeholder="Nama Anda"><br><br>
            
            <label for="nim">No Induk Mahasiswa (NIM):</label>
            <input type="number" id="nim" name="nim" placeholder="123456789"><br><br>
            
            <label for="alamat">Alamat Mahasiswa:</label>
            <textarea id="alamat" name="alamat" placeholder="Alamat Anda"></textarea><br><br>
            
            <label for="tgl">Tanggal Lahir:</label>
            <select id="tgl" name="tgl">
                <option value="01">01</option>
                <!-- Add more options as needed -->
            </select>
            <select id="bulan" name="bulan">
                <option value="Januari">Januari</option>
                <!-- Add more options as needed -->
            </select>
            <select id="tahun" name="tahun">
                <option value="1990">1990</option>
                <!-- Add more options as needed -->
            </select><br><br>
            
            <label>Jenis Kelamin:</label>
            <input type="radio" id="pria" name="jk" value="Pria">
            <label for="pria">Pria</label>
            <input type="radio" id="wanita" name="jk" value="Wanita">
            <label for="wanita">Wanita</label><br><br>
            
            <label for="foto">Upload Foto:</label>
            <input type="file" id="foto" name="foto"><br><br>
            
            <label for="website">URL Website:</label>
            <input type="url" id="website" name="website" placeholder="URL Website Anda"><br><br>
            
            <label for="pt">Perguruan Tinggi:</label>
            <input type="text" id="pt" name="pt"><br><br>
        </fieldset>
        
        <fieldset>
            <legend>Info Akun</legend>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Email Anda"><br><br>
            
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" placeholder="Username Anda"><br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Password Anda"><br><br>
            
            <label for="repeat-password">Ulangi Password:</label>
            <input type="password" id="repeat-password" name="repeat-password" placeholder="Password Anda"><br><br>
        </fieldset>
        
        <fieldset>
            <legend>Kemampuan Dasar</legend>
            <input type="checkbox" id="html" name="skills" value="HTML">
            <label for="html">HTML</label>
            <input type="checkbox" id="css" name="skills" value="CSS">
            <label for="css">CSS</label>
            <input type="checkbox" id="javascript" name="skills" value="Javascript">
            <label for="javascript">Javascript</label>
            <input type="checkbox" id="php" name="skills" value="PHP">
            <label for="php">PHP</label>
            <input type="checkbox" id="mysql" name="skills" value="MySQL">
            <label for="mysql">MySQL</label>
            <input type="checkbox" id="laravel" name="skills" value="Laravel">
            <label for="laravel">Laravel</label>
            <input type="checkbox" id="react-native" name="skills" value="React Native">
            <label for="react-native">React Native</label>
        </fieldset>
        
        <button type="reset">Reset</button>
        <button type="submit">Simpan</button>
    </form>
</body>
</html>

