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
    <P>NIK: 3216090512101746</P>
    <p>Kepala Keluarga: DARMAJI</p>
    <p>Alamat: Kp.Tanah Baru, Desa Karang Baru, Kecamatan Cikarang Utara, Kab.Bekasi, Provinsi Jawa Barat, RT 01/ RW 02</p>
    <br><br>
    <div id="orang"></div>
    <div class="tombol">
        <a href="home.md" class="login">
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
                    <td>DARMAJI</td>
                    <td>3216091810400002</td>
                    <td>LAKI-LAKI</td>
                    <td>BEKASI</td>
                    <td>18-10-1940</td>
                    <td>ISLAM</td>
                    <td>TAMAT SD/SEDERAJAT</td>
                    <td>WIRASWASTA</td>
                </tr>
                  <tr>
                    <td>2</td>
                    <td>MURNI</td>
                    <td>3216095202500007</td>
                    <td>PEREMPUAN</td>
                    <td>BEKASI</td>
                    <td>12-02-1950</td>
                    <td>ISLAM</td>
                    <td>TAMAT SD/SEDERAJAT</td>
                    <td>MENGURUS RUMAH TANGGA</td>
                </tr>
            </tbody>
        </table>
        `;
        document.getElementById("orang").innerHTML = tableHTML;
    </script>
</body>
</html>
