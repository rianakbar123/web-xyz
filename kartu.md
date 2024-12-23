<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>kartu keluarga</title>
    <style>
        table{
            width: 100%;
            border-collapse: collapse;
        }
        table,th,td{
            border: 1px solid black;
        }
        th,td{
            padding: 8px;
            text-align: left;
        }
        .tombol {
            margin-top: 10px;
        }
        .tombol tombol {
            padding: 20px 30px;
            margin: 0 5px;
            border: none;
            border-radius: 40px;
            cursor: pointer;
            height: 20px;
        }
        .tombol .login {
            background-color: rgb(43,191,254);
            color: #000;
            border-radius:1000vh;
            width: 20vh;
        }
    </style>
</head>
<body>
    <h1>KARTU KELUARGA</h1>
    <P>NIK: 3216092304120005</P>
    <p>Kepala Keluarga: JUHAERI</p>
    <p>Alamat: Kp.Tanah Baru, Desa Karang Baru, Kecamatan Cikarang Utara, Kab.Bekasi, Provinsi Jawa Barat, RT 01/ RW 02</p>
    <br><br>
    <div id="orang"></div>
    <div class="tombol">
        <a href="home.html" class="login">
            HOME
        </a>
    </div>
    <script>
        const tableHTML = `
        <table>
            <thead>
                <tr>
                    <th>NO</th>
                    <th>Nama Lengkap</th>
                    <th>NIK</th>
                    <th>JENIS KELAMIN</th> 
                    <th>TEMPAT LAHIR</th>
                    <th>TANGGAL LAHIR</th>
                    <th>AGAMA</th>
                    <th>PENDIDIDKAN</th>
                    <th>JENIS PEKEJAAN</th>   
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>JUHAERI</td>
                    <td>3216090708820005</td>
                    <td>LAKI-LAKI</td>
                    <td>BEKASI</td>
                    <td>07-08-1982</td>
                    <td>ISLAM</td>
                    <td>SLTA/SEDERAJAT</td>
                    <td>WIRASWASTA</td>
                </tr>
                  <tr>
                    <td>2</td>
                    <td>NITA</td>
                    <td>3216095408850013</td>
                    <td>PEREMPUAN</td>
                    <td>BEKASI</td>
                    <td>14-08-1985</td>
                    <td>ISLAM</td>
                    <td>SLTA/SEDERAJAT</td>
                    <td>MENGURUS RUMAH TANGGA</td>
                </tr>
                  <tr>
                    <td>3</td>
                    <td>MUHAMMAD RIAN AKBAR</td>
                    <td>3216090303080009</td>
                    <td>LAKI-LAKI</td>
                    <td>BEKASI</td>
                    <td>03-03-2008</td>
                    <td>ISLAM</td>
                    <td>BELUM TAMAT SD/SEDERAJAT</td>
                    <td>PELAJAR/MAHASISWA</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>ADE RIANTY PUTRI</td>
                    <td>3216095810110003</td>
                    <td>PEREMPUAN</td>
                    <td>BEKASI</td>
                    <td>18-10-2011</td>
                    <td>ISLAM</td>
                    <td>BELUM TAMAT SD/SEDERAJAT</td>
                    <td>PELAJAR/MAHASISWA</td>
                </tr>
                 <tr>
                    <td>5</td>
                    <td>RISKA APRIYANTI</td>
                    <td>3216095903140004</td>
                    <td>PEREMPUAN</td>
                    <td>BEKASI</td>
                    <td>19-03-2014</td>
                    <td>ISLAM</td>
                    <td>TIDAK/BELUM SEKOLAH</td>
                    <td>BELUM/TIDAK BEKERJA</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>SITI AISYAH</td>
                    <td>3216095001210003</td>
                    <td>PEREMPUAN</td>
                    <td>BEKASI</td>
                    <td>10-01-2021</td>
                    <td>ISLAM</td>
                    <td>TIDAK/BELUM SEKOLAH</td>
                    <td>BELUM/TIDAK BEKERJA</td>
                </tr>
               
            </tbody>
        </table>
        `;
        document.getElementById("orang").innerHTML = tableHTML;
    </script>
</body>
</html>
