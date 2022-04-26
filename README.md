#深碗網頁
程式設計-深碗(網頁)
💡
HTML是一種標記型文檔，用來標記一個文本內容意義的文檔。最外層的HTML標籤標記整個文檔的內容屬於HTML。裡面的head就是文檔的屬性，如文檔類型，文檔大小，文檔名等；body就是文檔主要內容。而後來HTML被用作網頁開發，因此head就成了描述網站屬性的標記，而body就成了網站內容的標記。

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>My test page</title>
    <style>
        
    </style>
</head>

<body>
    <table style="border:3px #cccccc solid;" cellpadding="10" border='1'>
        <tr>
            <th>班級</th>
            <th>學號</th>
            <th>姓名</th>
        </tr>
        <tr>
            <td>一甲</td>
            <td>410411XX</td>
            <td>XXX</td>
        </tr>
    </table>
</body>

</html>
https://www.webtech.tw/info.php?tid=HTML_head_標籤

<!DOCTYPE html> — 文件類型（doctype）文件類型是用來連結一些應遵守的規則，有點像自動校正的功能。然而，現在大家其實不太管文件類型，它就是個必須放在程式碼中的東西，現階段大家只需要知道這點就夠了。
<html></html> — <html> 元素，又被視為根元素（root element），包含了所有顯示在這個頁面上的內容。
<head></head> — <head> 元素，裡面放的是你想涵括的重要資訊，但不會顯示於網頁瀏覽者眼前的。例如，顯示於搜尋結果的關鍵字、頁面說明、CSS、字元實體集...等。
<body></body> — <body> 元素，包含了所有會顯示於網頁瀏覽者眼前的內容。 無論是文字、圖片、影面、互動遊戲...等。
<meta charset="utf-8"> — 這個元素指定了你的文件使用utf-8字元編碼， 建議大家都要使用這個元素，它會幫助你免去許多文字無法正確呈現的煩惱。
<title></title> — 呈現於網頁瀏覽者眼前的網頁標題。
3/10

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script>
        function check() {
            if (document.form1.phone.value == "") {
                alert("連絡電話,不可空白!");
                return false;
            }
            return true;
        }
    </script>
</head>

<body>
    0<br>1
    <br>2
    <p>A</p>
    <p>B</p>
    <form name="form1" action="" onsubmit="return check();">
        <table style="margin-top:50px;" border="5" align="center">
            <tr>
                <td colspan="2" align="center">民宿預約網</td>
            </tr>
            <tr>
                <td>姓名</td>
                <td><input type="text" name="name"></td>
            </tr>
            <tr>
                <td>連絡電話</td>
                <td><input type="text" name="phone"></td>
            </tr>
            <tr>
                <td>入住日期</td>
                <td><input type="date" name="checkIn"></td>
            </tr>
            <tr>
                <td>退房日期</td>
                <td><input type="time" name="checkOut"></td>
            </tr>
            <tr>
                <td><input type="submit" value="確認預約"></td>
                <td></td>
            </tr>
        </table>
    </form>
</body>

</html>
</html>
<form name="form1" action="" onsubmit="return check();"> — 藉由抓取submit回傳的功能，按下按鈕後執行回傳(type=”submit”)的動作，並且呼叫寫好的名為”check”的功能。


3/17

<!doctype html>
<html lang="en">

<head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.0.2 -->
    <!--link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous"!-->
    <style>
        .jumbotron3 {
            padding: 8rem 8rem;
            margin-bottom: 2rem;
            background-color: #47be5b3a;
            border-radius: .5rem;
        }
    </style>
</head>

<body>
    <div class="container" style="margin-top:100px;">
        <div class="jumbotron3" style="box-shadow: 5px 10px #030303af">
            <h1 class="display-4">Hello, world!</h1>
            <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
            <hr class="my-4">
            <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
            <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
        </div>
    </div>

    <!-- Bootstrap JavaScript Libraries -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
</body>

</html>
bootstrap的應用，詳細內容可以到官網去查詢
3/24 Navbar


<!doctype html>
<html lang="en">

<head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.0.2 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

</head>

<body>

    <!-- Bootstrap JavaScript Libraries -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">首頁</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>

                </ul>
                <form class="d-flex">

                    <button data-bs-toggle="modal" data-bs-target="#exampleModal" class="btn btn-outline-success" type="button">登入</button>
                </form>
            </div>
        </div>
    </nav>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title mx-auto" id="exampleModalLabel">會員帳號登入</h5>

                </div>
                <div class="modal-body">
                    <form>
                        <div class="mb-3">
                            <label for="exampleInputEmail1" class="form-label">帳號</label>
                            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">

                        </div>
                        <div class="mb-3">
                            <label for="exampleInputPassword1" class="form-label">密碼</label>
                            <input type="password" class="form-control" id="exampleInputPassword1">
                        </div>
                        <div class="mb-3 form-check">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1">記住我</label>
                        </div>

                        <div class="text-center">
                            <button type="submit" class="btn btn-primary">登入</button>
                            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">關閉</button>
                        </div>
                    </form>
                </div>

            </div>
        </div>
    </div>
</body>

</html>
如何觸發按鈕，並呼叫另一個浮動視窗

3/31 Carousel
https://stackoverflow.com/questions/30538967/how-to-center-image-in-carousel


<!doctype html>
<html lang="en">

<head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.0.2 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <style>
        .carousel-item img {
            margin: auto;
        }
    </style>
</head>

<body>

    <!-- Bootstrap JavaScript Libraries -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <nav class="navbar navbar-expand-lg navbar-dark bg-danger ">
        <div class="container-fluid ">
            <a class=" navbar-brand " href="# ">Navbar</a>
            <button class="navbar-toggler " type="button " data-bs-toggle="collapse " data-bs-target="#navbarSupportedContent " aria-controls="navbarSupportedContent " aria-expanded="false " aria-label="Toggle navigation ">
                <span class="navbar-toggler-icon "></span>
            </button>
            <div class="collapse navbar-collapse " id="navbarSupportedContent ">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0 ">
                    <li class="nav-item ">
                        <a class="nav-link active " aria-current="page " href="# ">首頁</a>
                    </li>
                    <li class="nav-item ">
                        <a class="nav-link " href="# ">Link</a>
                    </li>
                    <li class="nav-item dropdown ">
                        <a class="nav-link dropdown-toggle " href="# " id="navbarDropdown " role="button " data-bs-toggle="dropdown " aria-expanded="false ">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu " aria-labelledby="navbarDropdown ">
                            <li><a class="dropdown-item " href="# ">Action</a></li>
                            <li><a class="dropdown-item " href="# ">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider ">
                            </li>
                            <li><a class="dropdown-item " href="# ">Something else here</a></li>
                        </ul>
                    </li>

                </ul>
                <form class="d-flex ">

                    <button data-bs-toggle="modal " data-bs-target="#exampleModal " class="btn btn-outline-success " type="button ">登入</button>
                </form>
            </div>
        </div>
    </nav>

    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="image/P1.png" class="d-block w-50" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image/P2.png" class="d-block w-50" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image/P3.jpg" class="d-block w-50" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <!-- Modal -->
    <div class="modal fade " id="exampleModal " tabindex="-1 " aria-labelledby="exampleModalLabel " aria-hidden="true ">
        <div class="modal-dialog ">
            <div class="modal-content ">
                <div class="modal-header ">
                    <h5 class="modal-title mx-auto " id="exampleModalLabel ">會員帳號登入</h5>

                </div>
                <div class="modal-body ">
                    <form>
                        <div class="mb-3 ">
                            <label for="exampleInputEmail1 " class="form-label ">帳號</label>
                            <input type="email " class="form-control " id="exampleInputEmail1 " aria-describedby="emailHelp ">

                        </div>
                        <div class="mb-3 ">
                            <label for="exampleInputPassword1 " class="form-label ">密碼</label>
                            <input type="password " class="form-control " id="exampleInputPassword1 ">
                        </div>
                        <div class="mb-3 form-check ">
                            <input type="checkbox " class="form-check-input " id="exampleCheck1 ">
                            <label class="form-check-label " for="exampleCheck1 ">記住我</label>
                        </div>

                        <div class="text-center ">
                            <button type="submit " class="btn btn-primary ">登入</button>
                            <button type="button " class="btn btn-secondary " data-bs-dismiss="modal ">關閉</button>
                        </div>
                    </form>
                </div>

            </div>
        </div>
    </div>

</body>

</html>
4/7-14 Bootstrap youtube Embeds responsive (官網連結)
首頁
<!doctype html>
<html lang="en">

<head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.0.2 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <style>
        .carousel-item img {
            margin: auto;
        }
    </style>

</head>

<body>

    <!-- Bootstrap JavaScript Libraries -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">NavBar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="product.html">商品介紹</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>

                </ul>
                <form class="d-flex">
                    <button class="btn btn-outline-success" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal">LogIn</button>
                </form>
            </div>
        </div>
    </nav>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true" style="margin:auto;">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title mx=-auto" id="exampleModalLabel">帳號登入</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <form>
                    <div class="mb-3">
                        <label for="exampleInputEmail1" class="form-label">帳號</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We'll "never" share your email with anyone else.</div>
                    </div>
                    <div class="mb-3">
                        <label for="exampleInputPassword1" class="form-label">密碼</label>
                        <input type="password" class="form-control" id="exampleInputPassword1">
                    </div>
                    <div class="mb-3 form-check">
                        <input type="checkbox" class="form-check-input" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1">記憶</label>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="btn btn-primary">認證</button>
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    </div>
                </form>
                <div class="modal-footer">

                </div>
            </div>
        </div>
    </div>

    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="image/P1.png" class="d-block w-70" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image/P2.png" class="d-block w-70" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="image/P3.jpg" class="d-block w-70" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <div class="container">
        <div class="row">
            <h1 class="text-center my-5">最新上傳影片</h1>
            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <!--總長度12 每種不同框架長度為6/12、4/12...等-->
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>
        </div>

        <div class="row">
            <h1 class="text-center my-5">最熱門上傳影片</h1>
            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ti_VHbuyTAs" allowfullscreen></iframe>
                </div>
            </div>
        </div>

    </div>

    <div class="footer">
        <p class="bg-danger text-white text-center p-1 fixed-bottom">版權宣告，翻印必究</p>
    </div>

</html>
分頁1
<!doctype html>
<html lang="en">

<head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.0.2 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <style>
        .carousel-item img {
            margin: auto;
        }
    </style>

</head>

<body>

    <!-- Bootstrap JavaScript Libraries -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">NavBar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="product.html">商品介紹</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>

                </ul>
                <form class="d-flex">
                    <button class="btn btn-outline-success" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal">LogIn</button>
                </form>
            </div>
        </div>
    </nav>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true" style="margin:auto;">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title mx=-auto" id="exampleModalLabel">帳號登入</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <form>
                    <div class="mb-3">
                        <label for="exampleInputEmail1" class="form-label">帳號</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We'll "never" share your email with anyone else.</div>
                    </div>
                    <div class="mb-3">
                        <label for="exampleInputPassword1" class="form-label">密碼</label>
                        <input type="password" class="form-control" id="exampleInputPassword1">
                    </div>
                    <div class="mb-3 form-check">
                        <input type="checkbox" class="form-check-input" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1">記憶</label>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="btn btn-primary">認證</button>
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    </div>
                </form>
                <div class="modal-footer">

                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <div class="row">
            <h1 class="text-center my-5">最新上傳影片</h1>
            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="card" style="width: 18rem;">
                    <img src="http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">商品標題</h5>
                        <p class="card-text">商品規格與特色介紹</p>
                        <a href="#" class="btn btn-primary">GOGO!</a>
                    </div>
                </div>

            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="card" style="width: 18rem;">
                    <img src="http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">商品標題</h5>
                        <p class="card-text">商品規格與特色介紹</p>
                        <a href="#" class="btn btn-primary">GOGO!</a>
                    </div>
                </div>
            </div>

            <div class="col-sm-12 col-md-6 col-lg-4 mb-5">
                <div class="card" style="width: 18rem;">
                    <img src="http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">商品標題</h5>
                        <p class="card-text">商品規格與特色介紹</p>
                        <a href="#" class="btn btn-primary">GOGO!</a>
                    </div>
                </div>

            </div>
        </div>
    </div>
    <div class="footer">
        <p class="bg-danger text-white text-center p-1 fixed-bottom">版權宣告，翻印必究</p>
    </div>

</html>



lg是螢幕目前最大的規格，即便沒有定義也會有。https://getbootstrap.com/docs/5.0/components/modal/#embedding-youtube-videos



Github教學








接著save檔案，等待網站跑完就好了。
