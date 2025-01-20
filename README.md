
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
<title>Hồ sơ thí sinh | Kỳ thi đánh giá năng lực</title>
<meta http-equiv="refresh" content="3600">
<meta name="author" content="thanhdungintel@gmail.com" />
<meta name="keywords" content="Tuyển sinh, Thi đánh giá năng lực" />
<meta name="description" content="Thi đánh giá năng lực" />
<meta name="robots" content="noindex,nofollow">
<link rel="shortcut icon" href="/dgnl/images/public/favicon.png" />
    <!-- Font Awesome -->
    <link rel="stylesheet" href="/dgnl/fonts/awesome/all.min.css" />
    <!-- Google Fonts Roboto -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" />
    <link href="/dgnl/js/plugins/gritter/jquery.gritter.min.css" rel="stylesheet" />
    <link href="/dgnl/js/plugins/swal2/sweetalert2.min.css" rel="stylesheet" />
    <link href="/dgnl/css/loading.css" rel="stylesheet" />
    <!-- MDB -->
    <link rel="stylesheet" href="/dgnl/theme/mdb/css/mdb.min.css" />
    <link href="/dgnl/css/common.css" rel="stylesheet" />
    <!-- Global site tag (gtag.js) - Google Analytics
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-138055486-1"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());
        gtag('config', 'UA-138055486-1');
    </script>
  
</head>
<body>
    <div class="loader" style="display: none;">
</div>
    <!--Main Navigation-->
    <header>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white fixed-top">
        <div class="container-fluid">
            <!-- Navbar brand -->
            <a class="navbar-brand" href="/dgnl/app/home">
                <img src="/dgnl/images/public/vnuhcm.png" height="45" alt="" loading="lazy"
                    style="margin-top: -3px;" />
            </a>
            <button class="navbar-toggler" type="button" data-mdb-toggle="collapse" data-mdb-target="#navbarExample01"
                aria-controls="navbarExample01" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fas fa-bars"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarExample01">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
    <li class="nav-item active">
        <a class="nav-link" aria-current="page" href="/dgnl/app/home">Trang chủ</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="https://drive.google.com/file/d/1W-zw9HjsjgvrQXj3gLfulWi6EKEQiYvB/view" rel="nofollow"
            target="_blank">Hướng dẫn</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" href="/dgnl/thong-tin-ky-thi" target="_blank">Giới thiệu về
            kỳ thi</a>
    </li>
    
</ul>
                <ul class="navbar-nav d-flex flex-row">
                    <!-- Icons -->
                    <!-- Icons -->
<li class="nav-item me-3 me-lg-0">
    <a class="nav-link" href="http://cete.vnuhcm.edu.vn/thi-danh-gia-nang-luc.html" rel="nofollow" target="_blank">
        <i class="fas fa-home"></i>
    </a>
</li>
<li class="nav-item me-3 me-lg-0">
    <a class="nav-link" href="https://www.facebook.com/vnuhcm.info/" rel="nofollow" target="_blank">
        <i class="fab fa-facebook-f"></i>
    </a>
</li>
<li class="nav-item me-3 me-lg-0">
    <a class="nav-link" href="mailto:thinangluc@vnuhcm.edu.vn" rel="nofollow" target="_blank">
        <i class="fas fa-envelope"></i>
    </a>
</li>
                    <li class="nav-item">
                        <a class="nav-link dropdown-toggle d-flex align-items-center dropdown-userinfo">
                            <img src="/dgnl/images/public/favicon.png" style="width: 24px;"
                                class="avatar avatar-24 photo rounded-circle">
                            <span class="d-md-inline mx-1">PHAN ANH KHOA</span>
                        </a>
                        <div class="dropdown-menu dropdown-menu-end p-0">
                            <a class="dropdown-item" href="/dgnl/app/my-profile">Hồ sơ cá nhân</a>
                            <a class="dropdown-item" href="/dgnl/app/my-account">Thông tin tài khoản</a>
                            <a class="dropdown-item" href="/dgnl/app/event-history">Nhật ký sử dụng</a>
                            <hr class="m-0">
                            <a class="dropdown-item mdb-logout-button" href="/dgnl/logout">Đăng xuất</a>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Navbar -->
    <!-- Jumbotron -->
    <div id="intro" class="p-5 text-center bg-light">
        <h1 class="mb-0 h4 header-banner">KỲ THI ĐÁNH GIÁ NĂNG LỰC NĂM
            <script>document.write(new Date().getFullYear());</script>
        </h1>
    </div>
</header>
    <!--Main Navigation-->
    <!--Main layout-->
    <main class="mt-4 mb-5">
        <div class="container">
            <!--Grid row-->
            <div class="row">
                <!--Grid column-->
                <div class="col-md-12 mb-4">
                    <!--Content Page-->
            <section>
                <h4>Hồ sơ thí sinh</h4>
                <div class="alert alert-warning" role="alert" data-mdb-color="warning">
                    <i class="fas fa-exclamation-triangle me-3"></i>Lưu ý:
                    <p id="lblNoteMessage" style="display: none; font-weight: bold; color: red;">
                    </p>
                    <p>
                        Các thông tin nhập vào phải là tiếng Việt có
                        dấu.
                    </p>
                </div>
                <section id="section-tabs-profile">
                    <section class="pb-4">
                        <div class="bg-white border rounded-5">
                            <section class="w-100 p-4 pb-4">
                                <!-- Tabs navs -->
                                <ul class="nav nav-tabs mb-3" id="tabForm" role="tablist">
                                    <li class="nav-item" role="presentation">
                                        <a class="nav-link active" id="tab-1" data-mdb-toggle="tab" href="#tab-profile"
                                            role="tab" aria-controls="tab-profile" aria-selected="true"><i
                                                class="fas fa-user-tie fa-fw me-2"></i>Thông tin cá nhân</a>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <a class="nav-link" id="tab-2" data-mdb-toggle="tab" href="#tab-address"
                                            role="tab" aria-controls="tab-address" aria-selected="false"><i
                                                class="fas fa-home fa-fw me-2"></i>Thông tin
                                            liên lạc</a>
                                    </li>
                                    <li class="nav-item" role="presentation">
                                        <a class="nav-link" id="tab-3" data-mdb-toggle="tab" href="#tab-adimission"
                                            role="tab" aria-controls="tab-adimission" aria-selected="false"><i
                                                class="fas fa-graduation-cap fa-fw me-2"></i>Lịch sử học tập THPT</a>
                                    </li>
                                    <li class="nav-item" role="presentation" id="tabThongTinUuTien"
                                        style="display: none;">
                                        <a class="nav-link" id="tab-4" data-mdb-toggle="tab" href="#tab-ThongTinUuTien"
                                            role="tab" aria-controls="tab-ThongTinUuTien" aria-selected="false"><i
                                                class="fas fa-info fa-fw me-2"></i>Thông tin ưu tiên</a>
                                    </li>
                                </ul>
                                <!-- Tabs navs -->
                                <!-- Tabs content -->
                                <div class="tab-content" id="tabFormContent">
                                    <div class="tab-pane fade show active" id="tab-profile" role="tabpanel"
                                        aria-labelledby="tab-1">
                                        <!--Profile-->
                                        <div class="bg-white border rounded-5">
                                            <section class="w-100 px-4 pb-4">
                                                <form id="frmProfile" name="frmProfile">
                                                    <div class="row">
                                                        <div class="col-md-4 pt-4">
                                                            <label class="form-label" for="txtHoVaTen">Họ
                                                                và tên</label>
                                                            <input class="form-control" name="txtHoVaTen"
                                                                id="txtHoVaTen" type="text"
                                                                placeholder="Ví dụ: Nguyễn Văn An"
                                                                style="text-transform: uppercase;" />
                                                        </div>
                                                        <div class="col-md-4 pt-4 datepicker-birthday"
                                                            data-mdb-format="dd/mm/yyyy" data-mdb-toggle-button="false">
                                                            <label class="form-label" for="txtNgayThangNamSinh">Ngày
                                                                sinh</label>
                                                            <input class="form-control" name="txtNgayThangNamSinh"
                                                                id="txtNgayThangNamSinh" type="text"
                                                                placeholder="Ví dụ: 20/01/2001" maxlength="10"
                                                                data-mdb-toggle="datepicker" readonly />

                                                        </div>
                                                        <div class="col-md-4">
                                                            <section class="pt-4">
                                                                <label class="form-label">Giới tính</label>
                                                                <select class="select" name="radPhai" id="radPhai">
                                                                    <option value="0">Nam</option>
                                                                    <option value="1">Nữ</option>
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-2 pt-4" style="display: none;">
                                                            <label class="form-label" for="txtNgaySinh">Ngày
                                                                sinh</label>
                                                            <input class="form-control no-validate" name="txtNgaySinh"
                                                                id="txtNgaySinh" type="text" placeholder="Ví dụ: 20"
                                                                maxlength="2" />
                                                        </div>
                                                        <div class="col-md-2 pt-4" style="display: none;">
                                                            <label class="form-label" for="txtThangSinh">Tháng
                                                                sinh</label>
                                                            <input class="form-control no-validate" name="txtThangSinh"
                                                                id="txtThangSinh" type="text" placeholder="Ví dụ: 12"
                                                                maxlength="2" />
                                                        </div>
                                                        <div class="col-md-2 pt-4" style="display: none;">
                                                            <label class="form-label" for="txtNamSinh">Năm
                                                                sinh</label>
                                                            <input class="form-control no-validate" name="txtNamSinh"
                                                                id="txtNamSinh" type="text" placeholder="Ví dụ: 2000"
                                                                maxlength="4" />
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-4">
                                                            <section class="pt-4">
                                                                <label class="form-label">Tỉnh/Thành phố
                                                                    nơi sinh</label>
                                                                <select class="select" name="cboTinhTpNoiSinh"
                                                                    id="cboTinhTpNoiSinh" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-2 pt-4">
                                                            <section>
                                                                <label class="form-label">Dân tộc</label>
                                                                <select class="select" name="cboDanToc" id="cboDanToc"
                                                                    data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-2 pt-4">
                                                            <section>
                                                                <label class="form-label">Tôn giáo</label>
                                                                <select class="select" name="cboTonGiao" id="cboTonGiao"
                                                                    data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-4 pt-4">
                                                            <section>
                                                                <label class="form-label">Quốc tịch</label>
                                                                <select class="select" name="cboQuocTich"
                                                                    id="cboQuocTich" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-4 pt-4">
                                                            <label class="form-label" for="txtSoCMND">Số Thẻ căn
                                                                cước/CCCD</label>
                                                            <input class="form-control" name="txtSoCMND" id="txtSoCMND"
                                                                type="text" readonly />
                                                        </div>
                                                        <div class="col-md-4 pt-4 datepicker-cccd"
                                                            data-mdb-format="dd/mm/yyyy" data-mdb-toggle-button="false">
                                                            <label class="form-label" for="txtNgayCapSoCMND">Ngày
                                                                cấp Thẻ căn cước/CCCD</label>
                                                            <input class="form-control" name="txtNgayCapSoCMND"
                                                                id="txtNgayCapSoCMND" maxlength="10" type="text"
                                                                data-mdb-toggle="datepicker" />
                                                        </div>
                                                        <div class="col-md-4 pt-4">
                                                            <section>
                                                                <label class="form-label">Nơi cấp Thẻ căn cước/CCCD</label>
                                                                <select class="select" name="cboNoiCapSoCMND"
                                                                    id="cboNoiCapSoCMND" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row text-center">
                                                        <div class="col-md-6 pt-4">
                                                            <div class="bg-image" data-alt="CMND_Mat_Truoc">
                                                                <img name="imgCMNDMatTruoc" id="imgCMNDMatTruoc"
                                                                    src="/dgnl/images/pages/app/no-image.png"
                                                                    class="img-fluid rounded" alt="Mặt trước"
                                                                    style="width: 50%;" />
                                                                <div class="mask"
                                                                    style="background-color: rgba(0, 0, 0, 0.6);">
                                                                    <div
                                                                        class="d-flex justify-content-center align-items-center h-100">
                                                                        <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                        </p>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                            <p class="text-muted small pt-2"><i
                                                                    class="fa fa-trash pointer text-info"
                                                                    id="bntRemoveImageCMNDTruoc" title="Xóa hình"></i>
                                                                Hình mặt trước Thẻ căn cước/CCCD
                                                            </p>
                                                        </div>
                                                        <div class="col-md-6 pt-4">
                                                            <div class="bg-image" data-alt="CMND_Mat_Sau">
                                                                <img name="imgCMNDMatSau" id="imgCMNDMatSau"
                                                                    src="/dgnl/images/pages/app/no-image.png"
                                                                    class="img-fluid rounded" alt="Mặt sau"
                                                                    style="width: 50%;" />
                                                                <div class="mask"
                                                                    style="background-color: rgba(0, 0, 0, 0.6);">
                                                                    <div
                                                                        class="d-flex justify-content-center align-items-center h-100">
                                                                        <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                        </p>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                            <p class="text-muted small pt-2"><i
                                                                    class="fa fa-trash pointer text-info"
                                                                    id="bntRemoveImageCMNDSau" title="Xóa hình"></i>
                                                                Hình mặt sau Thẻ căn cước/CCCD
                                                            </p>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12">
                                                            <p class="note note-light text-start">
                                                                - Trường hợp có nhu cầu đổi số <b>Thẻ căn cuớc/CCCD</b>
                                                                vui lòng
                                                                liên
                                                                hệ Trung tâm theo các số hotline hoặc email để được hỗ
                                                                trợ.
                                                                <br>
                                                                - Hình Thẻ căn cước/CCCD tải lên phải <strong>rõ nội
                                                                    dung</strong> và có
                                                                kích thước
                                                                <strong>≥400px</strong>.
                                                            </p>
                                                        </div>
                                                    </div>
                                                </form>
                                            </section>
                                        </div>
                                        <!--Profile-->
                                    </div>
                                    <div class="tab-pane fade" id="tab-address" role="tabpanel" aria-labelledby="tab-2">
                                        <!--Address-->
                                        <div class="bg-white border rounded-5">
                                            <section class="w-100 px-4 pb-4">
                                                <form id="frmAddress" name="frmAddress">
                                                    <div class="row">
                                                        <div class="col-md-6 pt-4">
                                                            <label class="form-label" for="txtEmail">Email liên
                                                                lạc</label>
                                                            <input class="form-control" name="txtEmail" id="txtEmail"
                                                                type="email" readonly />
                                                        </div>
                                                        <div class="col-md-6 pt-4">
                                                            <label class="form-label" for="txtDienThoaiLienLac">Điện
                                                                thoại liên lạc</label>
                                                            <input class="form-control" name="txtDienThoaiLienLac"
                                                                id="txtDienThoaiLienLac" type="text" />
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12">
                                                            <section class="pt-4">
                                                                <label class="form-label"><b>Địa chỉ thường
                                                                        trú:</b></label>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Tỉnh/Thành
                                                                    phố</label>
                                                                <select class="select" name="cboTinhTpThuongTru"
                                                                    id="cboTinhTpThuongTru" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Quận/Huyện</label>
                                                                <select class="select" name="cboQuanHuyenThuongTru"
                                                                    id="cboQuanHuyenThuongTru" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Phường/Xã</label>
                                                                <select class="select" name="cboPhuongXaThuongTru"
                                                                    id="cboPhuongXaThuongTru" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12 pt-4">
                                                            <label class="form-label" for="txtDiaChiThuongTru">Số
                                                                nhà, tên đường (*)</label>
                                                            <input class="form-control" name="txtDiaChiThuongTru"
                                                                id="txtDiaChiThuongTru" type="text" />
                                                        </div>
                                                        <figcaption
                                                            class="figure-caption text-start text-success mb-0 pb-0"
                                                            id="lblDiaChiThuongTru"></figcaption>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12">
                                                            <section class="pt-4">
                                                                <label class="form-label"><b>Địa chỉ liên
                                                                        lạc:</b></label>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Tỉnh/Thành
                                                                    phố</label>
                                                                <select class="select" name="cboTinhTpLienLac"
                                                                    id="cboTinhTpLienLac" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Quận/Huyện</label>
                                                                <select class="select" name="cboQuanHuyenLienLac"
                                                                    id="cboQuanHuyenLienLac" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-4">
                                                            <section class="pt-0">
                                                                <label class="form-label">Phường/Xã</label>
                                                                <select class="select" name="cboPhuongXaLienLac"
                                                                    id="cboPhuongXaLienLac" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12 pt-4">
                                                            <label class="form-label" for="txtDiaChiLienLac">Số
                                                                nhà, tên đường (*)</label>
                                                            <input class="form-control" name="txtDiaChiLienLac"
                                                                id="txtDiaChiLienLac" type="text" />
                                                        </div>
                                                        <figcaption
                                                            class="figure-caption text-start text-success mb-0 pb-0"
                                                            id="lblDiaChiLienLac"></figcaption>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12 pt-4">
                                                            <p class="note note-light text-start">
                                                                - (*) Chỉ nhập số nhà, tên đường, không cần nhập lại tên Phường/Xã, Quận/Huyện và Tỉnh/Thành phố.<br>
                                                                - Trường hợp không hiển thị tên Phường/Xã vui lòng liên
                                                                hệ Trung tâm theo các số hotline hoặc email để được hỗ
                                                                trợ.<br>
                                                                - Địa chỉ liên lạc này được dùng để liên hệ khi cần thiết.
                                                            </p>
                                                        </div>
                                                    </div>
                                                </form>
                                            </section>
                                        </div>
                                        <!--Address-->
                                    </div>
                                    <div class="tab-pane fade" id="tab-adimission" role="tabpanel"
                                        aria-labelledby="tab-3">
                                        <!--Adimission-->
                                        <div class="bg-white border rounded-5">
                                            <section class="w-100 px-4 pb-4">
                                                <form id="frmAdimission" name="frmAdimission">
                                                    <div class="row">
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <b>Lớp 10</b><br>
                                                                <label class="form-label">Tỉnh/Thành phố</label>
                                                                <select class="select" name="cboTinhTpTHPTLop10"
                                                                    id="cboTinhTpTHPTLop10" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <br>
                                                                <label class="form-label">Quận/Huyện</label>
                                                                <select class="select" name="cboQuanHuyenTHPTLop10"
                                                                    id="cboQuanHuyenTHPTLop10" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-6">
                                                            <section class="pt-4">
                                                                <br>
                                                                <label class="form-label">Trường
                                                                    THPT</label>
                                                                <select class="select" name="cboTruongTHPTLop10"
                                                                    id="cboTruongTHPTLop10" data-mdb-filter="true">
                                                                </select>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-3 mt-4 text-start">
                                                            <b>Lớp 11</b><br>
                                                            <div class="form-check form-switch">
                                                                <input class="form-check-input" type="checkbox"
                                                                    role="switch" name="chkTHPTLop11"
                                                                    id="chkTHPTLop11" />
                                                                <label class="form-check-label" for="chkTHPTLop11">Giống
                                                                    nơi học lớp 10</label>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <label class="form-label">Tỉnh/Thành phố</label>
                                                                <select class="select" name="cboTinhTpTHPTLop11"
                                                                    id="cboTinhTpTHPTLop11" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboTinhTpTHPTLop11"
                                                                    name="txtcboTinhTpTHPTLop11" style="display: none;"
                                                                    disabled>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <label class="form-label">Quận/Huyện</label>
                                                                <select class="select" name="cboQuanHuyenTHPTLop11"
                                                                    id="cboQuanHuyenTHPTLop11" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboQuanHuyenTHPTLop11"
                                                                    name="txtcboQuanHuyenTHPTLop11"
                                                                    style="display: none;" disabled>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-6">
                                                            <section class="pt-4">
                                                                <label class="form-label">Trường
                                                                    THPT</label>
                                                                <select class="select" name="cboTruongTHPTLop11"
                                                                    id="cboTruongTHPTLop11" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboTruongTHPTLop11"
                                                                    name="txtcboTruongTHPTLop11" style="display: none;"
                                                                    disabled>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-3 mt-4 text-start">
                                                            <b>Lớp 12</b><br>
                                                            <div class="form-check form-switch">
                                                                <input class="form-check-input" type="checkbox"
                                                                    role="switch" name="chkTHPTLop12"
                                                                    id="chkTHPTLop12" />
                                                                <label class="form-check-label" for="chkTHPTLop12">Giống
                                                                    nơi học lớp 11</label>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <label class="form-label">Tỉnh/Thành phố</label>
                                                                <select class="select" name="cboTinhTpTHPTLop12"
                                                                    id="cboTinhTpTHPTLop12" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboTinhTpTHPTLop12"
                                                                    name="txtcboTinhTpTHPTLop12" style="display: none;"
                                                                    disabled>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-3">
                                                            <section class="pt-4">
                                                                <label class="form-label">Quận/Huyện</label>
                                                                <select class="select" name="cboQuanHuyenTHPTLop12"
                                                                    id="cboQuanHuyenTHPTLop12" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboQuanHuyenTHPTLop12"
                                                                    name="txtcboQuanHuyenTHPTLop12"
                                                                    style="display: none;" disabled>
                                                            </section>
                                                        </div>
                                                        <div class="col-md-6">
                                                            <section class="pt-4">
                                                                <label class="form-label">Trường
                                                                    THPT</label>
                                                                <select class="select" name="cboTruongTHPTLop12"
                                                                    id="cboTruongTHPTLop12" data-mdb-filter="true">
                                                                </select>
                                                                <input class="form-control no-validate"
                                                                    id="txtcboTruongTHPTLop12"
                                                                    name="txtcboTruongTHPTLop12" style="display: none;"
                                                                    disabled>
                                                            </section>
                                                        </div>
                                                    </div>
                                                    <div class="row">
                                                        <div class="col-md-12 mt-4 text-start">
                                                            <div class="form-check form-check-inline col-md-4">
                                                                <input class="form-check-input" type="radio"
                                                                    name="radDoiTuongDuThi" id="radHSLop12" value="1"
                                                                    checked />
                                                                <label class="form-check-label" for="radHSLop12">Dự thi
                                                                    tốt nghiệp THPT năm <span
                                                                        id="lblDoiTuongThiTNTHPT">2025</span></label>
                                                            </div>

                                                            <div class="form-check form-check-inline">
                                                                <input class="form-check-input" type="radio"
                                                                    name="radDoiTuongDuThi" id="radDaTNLop12"
                                                                    value="2" />
                                                                <label class="form-check-label" for="radDaTNLop12">Đã
                                                                    tốt nghiệp THPT</label>
                                                            </div>

                                                            <div class="form-check form-check-inline"
                                                                style="display: none;">
                                                                <input class="form-check-input" type="radio"
                                                                    name="radDoiTuongDuThi" id="radDTKhac" value="3" />
                                                                <label class="form-check-label" for="radDTKhac">Đối
                                                                    tượng khác</label>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="row dvDoiTuongDuThiKhac">
                                                        <div class="col-md-12 mt-4">
                                                            <label class="form-label" for="txtDoiTuongDuThiKhac">Đối
                                                                tượng dự thi khác</label>
                                                            <input class="form-control no-validate"
                                                                name="txtDoiTuongDuThiKhac" id="txtDoiTuongDuThiKhac"
                                                                type="text" />
                                                        </div>
                                                    </div>
                                                    <div class="row dvDoiTuongDuThiTNNam">
                                                        <div class="col-md-12 mt-4">
                                                            <label class="form-label" for="txtDoiTuongDuThiTNNam">Năm
                                                                tốt nghiệp</label>
                                                            <input class="form-control no-validate"
                                                                name="txtDoiTuongDuThiTNNam" maxlength="4"
                                                                id="txtDoiTuongDuThiTNNam" type="text" />
                                                        </div>
                                                    </div>
                                                </form>
                                            </section>
                                        </div>
                                        <!--Adimission-->
                                    </div>
                                    <div class="tab-pane fade" id="tab-ThongTinUuTien" role="tabpanel"
                                        aria-labelledby="tab-4">
                                        <section class="w-100 px-4 pb-4">
                                            <form id="frmThongTinUuTien" name="frmThongTinUuTien">
                                                <div class="row">
                                                    <div class="col-md-12 mt-4 text-start">
                                                        <div class="form-check form-switch">
                                                            <input class="form-check-input" type="checkbox"
                                                                role="switch" name="chkHoKhauKhuVuc1"
                                                                id="chkHoKhauKhuVuc1" />
                                                            <label class="form-check-label" for="chkHoKhauKhuVuc1">Hộ
                                                                khẩu trên 18
                                                                tháng tại khu vực 1.</label>
                                                        </div>
                                                    </div>
                                                    <div class="col-md-12 mt-2 text-start">
                                                        <div class="form-check form-switch">
                                                            <input class="form-check-input" type="checkbox"
                                                                role="switch" name="chkHoKhauXaKhoKhan"
                                                                id="chkHoKhauXaKhoKhan" />
                                                            <label class="form-check-label" for="chkHoKhauXaKhoKhan">Hộ
                                                                khẩu trên 18
                                                                tháng tại xã đặc biệt khó khăn.</label>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-6">
                                                        <section class="pt-4">
                                                            <label class="form-label">Khu vực ưu
                                                                tiên</label>
                                                            <select class="select" name="cboKhuVucUuTien"
                                                                id="cboKhuVucUuTien" data-mdb-filter="true">
                                                            </select>
                                                        </section>
                                                    </div>
                                                    <div class="col-md-6">
                                                        <section class="pt-4">
                                                            <label class="form-label">Đối tượng ưu
                                                                tiên</label>
                                                            <select class="select" name="cboDoiTuongUuTien"
                                                                id="cboDoiTuongUuTien" data-mdb-filter="true">
                                                            </select>
                                                        </section>
                                                    </div>
                                                </div>
                                                <figcaption class="figure-caption text-start text-danger pt-4 mb-0 pb-0"
                                                    id="lblGhiChuUuTien">
                                                    <h6 class="lblKVUT">Chú thích cho khu vực ưu tiên:</h6>
                                                    <p class="lblKVUT">Khu vực ưu tiên</p>
                                                    <h6 class="lblDTUT">Chú thích cho đối tượng ưu tiên:</h6>
                                                    <p class="lblDTUT">Đối tượng ưu tiên</p>
                                                </figcaption>
                                                <div class="row">
                                                    <div class="col-md-12 pt-4">
                                                        <p class="note note-light text-start">
                                                            - Thí sinh cần khai báo khu vực ưu tiên, đối tượng ưu
                                                            tiên theo Quy chế tuyển sinh của Bộ GD&ĐT. Vui lòng xem
                                                            Quy chế tuyển sinh hiện hành của Bộ GD&ĐT <a
                                                                href="https://drive.google.com/file/d/1oZT8n0XpZiA65HnIRDJGxmb5BmAxWVjA/view?usp=sharing"
                                                                target="_blank">tại đây</a>.<br>
                                                            - Thí sinh hoàn toàn chịu trách nhiệm về đối tượng ưu
                                                            tiên, khu vực ưu tiên đã chọn lên hệ thống. Nếu sai
                                                            thông tin sẽ không được cộng điểm ưu tiên theo quy định.
                                                        </p>
                                                    </div>
                                                </div>
                                            </form>
                                        </section>
                                    </div>
                                    <div style="display: none;" class="tab-pane fade" id="tab-image" role="tabpanel"
                                        aria-labelledby="tab-5">
                                        <!--Upload-->
                                        <div class="bg-white border rounded-5">
                                            <section class="w-100 px-4 text-center pb-4">
                                                <div class="row">
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung1" title="Xóa hình"></i>
                                                            Hình minh chứng 1
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_1">
                                                            <img name="imgMinhChung1" id="imgMinhChung1"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 1"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung2" title="Xóa hình"></i>
                                                            Hình minh chứng 2
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_2">
                                                            <img name="imgMinhChung2" id="imgMinhChung2"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 2"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung3" title="Xóa hình"></i>
                                                            Hình minh chứng 3
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_3">
                                                            <img name="imgMinhChung3" id="imgMinhChung3"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 3"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung4" title="Xóa hình"></i>
                                                            Hình minh chứng 4
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_4">
                                                            <img name="imgMinhChung4" id="imgMinhChung4"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 4"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung5" title="Xóa hình"></i>
                                                            Hình minh chứng 5
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_5">
                                                            <img name="imgMinhChung5" id="imgMinhChung5"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 5"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-md-4 px-1 pt-4">
                                                        <p class="text-muted small"><i
                                                                class="fa fa-times pointer text-danger"
                                                                id="bntRemoveImageMinhChung6" title="Xóa hình"></i>
                                                            Hình minh chứng 6
                                                        </p>
                                                        <div class="bg-image" data-alt="MINH_CHUNG_6">
                                                            <img name="imgMinhChung6" id="imgMinhChung6"
                                                                src="/dgnl/images/pages/app/no-image.png"
                                                                class="img-fluid rounded" alt="Minh chứng 6"
                                                                style="height: 220px" />
                                                            <div class="mask"
                                                                style="background-color: rgba(0, 0, 0, 0.6);">
                                                                <div
                                                                    class="d-flex justify-content-center align-items-center h-100">
                                                                    <p class="text-white mb-0">Nhấn vào để cập nhật
                                                                    </p>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-12 pt-4">
                                                        <p class="note note-light text-start">
                                                            Trường hợp có nhiều tệp ảnh thì ghép các ảnh thành một tệp
                                                            ảnh duy nhất.
                                                        </p>
                                                    </div>
                                                </div>
                                            </section>
                                        </div>
                                        <!--Upload-->
                                    </div>
                                </div>
                                <!-- Tabs content -->
                            </section>
                            <div class="p-4 text-center border-top mobile-hidden">
                                <button id="bntSave" class="btn btn-primary">Lưu thông tin cá nhân</button>
                                <span>&nbsp;<i class="fa fa-arrow-right" aria-hidden="true"></i>&nbsp;</span>
                                <a class="btn btn-success" href="/dgnl/app/home">Quay về trang đăng ký</a>
                            </div>
                            
                        </div>
                    </section>
                </section>
            </section>
            <!-- Modal -->
            <div class="modal fade" id="frmUploadImage" tabindex="-1" aria-labelledby="frmUploadImageLabel"
                aria-hidden="true">
                <div class="modal-dialog small-modal-dialog">
                    <div class="modal-content small-modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="frmUploadImageLabel">Tải hình ảnh lên</h5>
                            <button type="button" class="btn-close" data-mdb-dismiss="modal"
                                aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-12">
                                    <div id="dvUploadImage" class="drop-area">
                                        <p>Nhấn chọn hình ảnh hoặc kéo thả
                                            vào đây...</p>
                                        <input accept="image/*" type="file" id="fUploadImage" class="fUploadImage"
                                            onchange="handleUploadImageFile(this.files)">
                                        <label class="btn btn-default" for="fUploadImage">Chọn
                                            hình ảnh</label>
                                    </div>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-md-12 pt-4 text-center">
                                    <img id="imgPreview" class="img-fluid rounded img-thumbnail" style="width: 320;"
                                        alt="Hình ảnh tải lên" />
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-secondary" data-mdb-dismiss="modal">Đóng
                                lại</button>
                            <button type="button" id="bntUploadImage" class="btn btn-primary">Xác nhận</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="modal fade" id="frmInfo" tabindex="-1" aria-labelledby="frmUploadImageLabel" aria-hidden="true">
                <div class="modal-dialog midle-modal-dialog">
                    <div class="modal-content midle-modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="frmUploadImageLabel">Thông tin mô tả</h5>
                            <button type="button" class="btn-close" data-mdb-dismiss="modal"
                                aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-12">
                                    <section class="d-flex justify-content-center w-100">
                                        <div class="container">
                                            <div class="alert" role="alert" data-mdb-color="success">
                                                <h4 class="alert-heading" id="lblHeaderInfo"></h4>
                                                <p class="mb-0" id="lblContentInfo"></p>
                                            </div>
                                        </div>
                                    </section>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-secondary" data-mdb-dismiss="modal">Đóng
                                lại</button>
                        </div>
                    </div>
                </div>
            </div> 
                </div>
                <!--Grid column-->
            </div>
            <!--Grid row-->
        </div>
    </main>
    <!--Main layout-->
    <!--Footer-->
    <footer class="bg-light text-lg-start">
    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
        &copy; 2023 Copyright:
        <a class="text-dark" href="/dgnl/home">Trung tâm Khảo thí và Đánh giá chất lượng đào tạo, ĐHQG-HCM</a>
    </div>
    <!-- Copyright -->
</footer>
    <!--Footer-->
    <!--Script-->
    <input type="hidden" id="hidPropertiesVendor"
        data-site-host="https://thinangluc.vnuhcm.edu.vn/dgnl/"
        data-api-host="https://thinangluc.vnuhcm.edu.vn/dgnl/api-dgnl/" data-api-token-access=""
        data-language="vi">
    <input type="hidden" id="hidGoogleReCaptcha"
        value="6LePazIjAAAAADh9FsVuTKlJ0TBhrlm7ZJicCmGm">
    <script src="/dgnl/js/plugins/jquery/jquery-3.6.1.min.js"></script>
    <script src="/dgnl/js/plugins/jquery/jquery-ui.min.js"></script>
    <script src="/dgnl/js/plugins/jquery/moment.min.js"></script>
    <script src="/dgnl/js/plugins/jquery/jquery.validate.min.js"></script>
    <script src="/dgnl/js/plugins/jquery/jquery.validate.min.js"></script>
    <script src="/dgnl/js/plugins/jquery/jquery.validator-method.js"></script>
    <script src="/dgnl/js/plugins/gritter/jquery.gritter.min.js"></script>
    <script src="/dgnl/js/plugins/swal2/sweetalert2.min.js"></script>
    <script src="/dgnl/theme/mdb/js/mdb.min.js"></script>
    <script src="/dgnl/js/pages/helper.js"></script>
    <script src="https://www.google.com/recaptcha/api.js?render=6LePazIjAAAAADh9FsVuTKlJ0TBhrlm7ZJicCmGm"></script><script src="/dgnl/js/plugins/jquery/jquery.facedetection.min.js"></script><script src="/dgnl/js/pages/app/profile.js?update=2025010901"></script>
</body>
</html>
