# sidarulekfinal.github.io
<!DOCTYPE html>
<html>
<head>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
	<meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="wiewport" content="width=device-width, inital-scale=1.0">
    
    <title>Sidar Ülek Sitesi</title>
</head>
<body>
    <nav class="navbar fixed-top navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
           Soli Elektronik Şikayet Formu
          </a>
        </div>
    </nav>
    <p>.</p>
    <div class="container">
        <div class="row mt-5">
          <div class="col">
            <form>
                <div class="mb-3">
                    <label class="form-label" for="myEmail">E-posta Adresiniz</label>
                    <input type="email" class="form-control" id="my Email" aria-describedby="emailHelper"
                    placeholder="e-posta adresinizi girin..">
                    <div class="form-text" id="emailHelper">E-posta adresiniz asla paylaşılmayacak </div>
                </div>
                <div class="mb-3">
                    <label class="form-label" for="my Password">Şifreniz</label>
                    <input type="password" class="form-control" id="myPassword" aria-describedby="passawordHelper"
                    placeholder="Şifrenizi girin..">
                </div>
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="remember">
                    <label class="form-check-label" for="remember">Beni Hatırla</label>
                </div>
                <div class="mb-3 row">
                    <label class="form-label col-sm-2 col-xl-1" for="myGender">Cihaz Türü:</label>
                    <div class="col-sm-10 col-xl-11">
                        <select id="myGender" class="form-select" aria-label="Açılır select kutusu">
                            <option selected>Cihaz Türünü Seç</option>
                            <option value="female">Televizyon</option>
                            <option value="male">Telefon</option>
                            <option value="male">Tablet</option>
                            <option value="male">Bilgisayar Aparatları</option>
                            <option value="male">Joystick</option>
                            <option value="male">Kulaklıklar</option>
                            <option value="male">Mikrofonlar</option>
                            <option value="male">Hopörlörler</option>
                            <option value="male">Kablo Çeşitleri</option>
                            <option value="male">Diğer(Açıklamada Belirtiniz)</option>
                        </select>
                    </div>
                </div>	
                <div class="mb-3 row">
                    <label class="form-label col-sm-2 col-xl-1" for="myGender">Şikayet Türü:</label>
                    <div class="col-sm-10 col-xl-11">
                        <select id="myGender" class="form-select" aria-label="Açılır select kutusu">
                            <option selected>Şikayet Türünü Seç</option>
                            <option value="female">Ekran Sıkıntısı</option>
                            <option value="male">Kablo Sıkıntısı</option>
                            <option value="male">Yazılım Sıkıntısı</option>
                            <option value="male">Batarya Sıkıntısı</option>
                            <option value="male">Dokunmatik Sıkıntısı</option>
                            <option value="male">Ses Sıkıntısı</option>
                            <option value="male">Sipariş Sıkıntısı</option>
                            <option value="male">Diğer(Açıklamada Belirtiniz)</option>
                        </select>
                    </div>
                </div>			        
                <div class="mb-3">
                    <label class="form-label" for="myArea"> Açıklama</label>
                    <textarea class="form-control" id="myArea" rows="4"> </textarea>
                    <div class="form-text" id="AçıklamaHelper">Şikayetinizi bu bölüme yazmalısınız. </div>
                </div>
                <div class="mb-3 row">
                    <label class="form-label col.sm.2 col-x1-1" for="myDosya"> Dosya Yükle:</label>
                    <input type="file" class="form-control" id="myDosya">
                    <div class="form-text" id="DosyaHelper">Yaşadığınız sıkıntıyı örnekleyenen bir fotoğraf ekleyebilirsiniz</div>
                </div>

                <button type="button" class="btn btn-success" data-bs-toggle="modal"
                data-bs-target="#myModal">Şikayet Formunu Gönder</button>
                    <div class="modal fade" tabindex="-1" id="myModal">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title">İşlem Bilgisi</h5>
                                </div>
                                <div class="modal-body">
                                <p>Şikayet formunuz tarafımıza iletilmiştir. En kısa zamanda belirtmiş olduğunuz e-mail adresinden tarafınıza geri dönüş yapılacaktır.(Belki de yapılmaz :D)</p>	
                                </div>
                            </div>
                        </div>
                    </div>
                </form>			
          </div>          		
        </div>
    </div>
    <p>.</p>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
