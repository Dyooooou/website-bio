<!DOCTYPE html>
<html>
    <head>
        <title>MY KISAH</title>
        <link rel="icon" type="image/jpeg" href="gambar/icon.jpeg">
        <link rel="stylesheet" href="style.css">
        
    </head>

    <body>
        <header>
            <h1>Welcome to my first web</h1>
            <a id="a1" href="bio.html" target="_blank">Biography</a>
            <a id="a2" href="contact.html" target="_blank">Contact</a>
            <!--<a href="game.html" target="_blank">Hobbies</a> -->
            <hr>
        </header>
        <div id="profile">
            <img id="photo" src="gambar/photo.jpeg" type="image/jpeg">
            <h1>Hey, it's me Dyou</h1>
            <pre>I am a Informatics Engineering student</pre>
            <pre>Bandung State of Polytechnic</pre>
        </div>
     
        <marquee>ini teks berjalan :o</marquee>

        
        <br>
        <br>
        <footer>
            <hr>
            <p>&copy; Julian Dio Saputra</p>
            <p> 
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
            Eveniet numquam dicta, deserunt ab quis consectetur sint aut labore tempora, 
            quasi impedit omnis amet minus quisquam quas commodi autem, deleniti temporibus.
            </p>
            <hr>
            <form enctype="multipart/form-data">
                <label for="Nama Lengkap">Nama Lengkap</label>
                <input type="text" id="Nama Lengkap"> <br>
                <label for="kel">Jenis Kelamin</label><br>
                <label for="lk">Laki-laki</label>
                <input type="radio" id="lk" value="Laki-laki" name="kel">
                <label for="pe">Perempuan</label>
                <input type="radio" id="pe" value="Perempuan" name="kel">
                <br>
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="akufreefire@gmail.com"><br>
                <label for="pw">Password Email</label>
                <input type="password" id="pw"><br>
                <label for="TTL">Tempat Lahir</label>
                <input type="text" id="TTL"><br>
                <label for="bday">Tanggal Lahir</label>
                <input type="date" id="bday"><br>
                <label for="Nama Ortu">Nama Orang Tua</label>
                <input type="text" id="Nama Ortu"><br>
                <label for="telp">Nomor Telepon</label>
                <input type="tel" id="telp"><br>
                <label for="Bank">Bank</label>
                <input type="number" id="Bank"><br>
                <label for="payment">Jenis Kartu</label>
                <select id="payment">
                    <option value="Visa">Visa</option>
                    <option value="Mastercard">Mastercard</option>
                </select><br>
                <label for="norek">Nomor Rekening</label>
                <input type="number" id="norek" minlength="16" maxlength="16" placeholder="1234 1234 1234 1234 1234" pattern="[0-9]{4} [0-9]{4} [0-9]{4} [0-9]{4}"><br>
                <label for="pin">Pin</label>
                <input type="number" minlength="6" maxlength="6" placeholder="123456"><br>
                
                <label for="ktp">Foto KTP</label>
                <input type="file" id="ktp" accept="image/png, image/jpeg, image/jpg"><br>
                <label for="subcribe">Setujui semua persyaratan</label>
                <input type="checkbox" id="subcribe"><br>
                <input type="submit" style="background-color: aqua;">
                <br>
                <input type="reset" style="background-color: red;">
            </form>
            <marquee>Form diatas jangan di isi!</marquee>
            <marquee>terlilit hutang? Hubungi 08923678423</marquee>
            <marquee>Jasa sedot wc hubungi 082123456789</marquee>
        </footer>
    </body>
</html>
