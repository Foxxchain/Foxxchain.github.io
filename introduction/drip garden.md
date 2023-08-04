<!DOCTYPE html>
<html lang="en">

<head>
    
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="apple-touch-icon" sizes="180x180" href="/images/favicon180.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/images/favicon32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/images/favicon16.png">

    <script type="text/javascript" src="/js/jquery-3.5.1.js?v=403"></script>
    <script type="text/javascript" src="/js/bootstrap.min.js?v=403"></script>
    <script type="text/javascript" src="/js/index.js?v=403"></script>
    <script type="text/javascript" src="/js/nav.js?v=403"></script>
    <script type="text/javascript" src="/js/class-message.js?v=403"></script>
    <!--<script src="web3/dist/web3.min.js?v=403"></script>-->
    <script src="https://cdn.jsdelivr.net/npm/web3@latest/dist/web3.min.js" type="text/javascript" async=""></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.2.1/dist/chart.umd.min.js"></script>

    <link type="text/css" rel="stylesheet" href="/css/pe-icon-7-stroke.min.css?v=403">
    <link type="text/css" rel="stylesheet" href="/css/bootstrap.min.css?v=403">
    <link type="text/css" rel="stylesheet" href="/fontawesome/css/all.css?v=403">
    <link type="text/css" rel="stylesheet" href="/css/themify-icons.css?v=403">
    <link type="text/css" rel="stylesheet" href="/css/cs-skin-elastic.css?v=403">
    <link type="text/css" rel="stylesheet" href="/css/nav.css?v=403">
    <link type="text/css" rel="stylesheet" href="/css/page.css?v=403">

    <!--<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4534127238636752"
        crossorigin="anonymous">
    </script>-->

    <title>The Crypto Co-operative</title>
    <script src="js/abi/abi-pcs-router-1.js?v=403"></script>
    <script src="js/abi/abi-pcs-router-2.js?v=403"></script>
    <script src="js/abi/abi-drip-garden.js?v=403"></script>
    <script src="js/abi/abi-drip-fountain.js?v=403"></script>
    <script src="js/abi/abi-token.js?v=403"></script>
    <script src="js/abi/abi-lp.js?v=403"></script>
    <script src="js/garden.js?v=403"></script>
    <script src="js/prices.js?v=403"></script>
    <link rel="stylesheet" href="css/garden.css?v=403">
</head>

<body onload="start()">
    <aside id="left-panel" class="left-panel"></aside>

    <div id="right-panel" class="right-panel">
        <header id="header" class="header">
            <div class="top-left">                    
                <a id="menuToggle" class="menutoggle"><i class="fa fa-bars"></i></a>
                <a id="color" class="color"><i class="fa fa-moon"></i></a>
                <h4 class="page-title"><i class="fa fa-seedling fa-neon"></i>Drip Garden</h4>
            </div>
            <div class="top-right">
    <a href="./"><img href="./" class="logo" src="/images/favicon16.png" alt="Logo"></a>
    <h4 class="logo-text">The Crypto Cooperative</h4>
</div>
        </header>

        <div class="content">

            <div id="loader" class="container">
    <div class="row">
        <div class="col-12">
            <div class="main-stat">
                <div class="loader"></div>
                <h3>Loading Data.. Please Wait</h3>
                <h3 id="process"></h3>
                <h4 id="process-wallet"></h4>
            </div>
        </div>
    </div>
</div>

            <div id="dash" class="container">

                <div class="row advert">
    <div class="col-xl-12 col-lg-12 col-md-12 col-sm-12">
        <div class="main-stat">
            <br>
            <h2><a href="https://defi.animalfarm.app/garden/0xC36217D24FC90C61bb0CD15f538C11792DB29a79"
                    target="_blank" rel="noopener noreferrer">
                    <h2>Depositing To The Garden? Support Our Team And Work By Clicking Here</h2>
                </a>
            </h2>
            <br>


            <h3>Add new wallets under the wallet manager to automatically pull your figures</h3>
            <br>
        </div>
    </div>
</div>


                <div class="row">
                    <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                        <div class="main-stat">
                            <h2 id="drip-price"></h2>
                            <h4>DRIP PRICE</h4>
                        </div>
                    </div>
                    <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                        <div class="main-stat">
                            <h2 id="dripbusd-price"></h2>
                            <h4>DRIP/BUSD PRICE</h4>
                        </div>
                    </div>
                    <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12">
                        <div class="main-stat">
                            <h2 id="plant-price"></h2>
                            <h4>PLANT PRICE</h4>
                        </div>
                    </div>
                    <div class="col-12">
                        <div class="main-stat">
                            <h2 id="start-date"></h2>
                            <h4>GARDEN STARTED</h4>
                        </div>
                    </div>
                </div>
                <div class="bubble">
                    <div class="row">
                        <div class="col-12">
                            <div class="main-stat">
                                <h1 class="title">My Garden</h1>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12">
                            <div class="main-stat">
                                <h2 id="last-action"></h2>
                                <h3 class="title">LAST ACTION</h3>
                            </div>
                            <br>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                            <div class="main-stat">
                                <h3 id="plants"></h3>
                                <h3 id="plants-lp"></h3>
                                <h3 id="plants-value"></h3>
                                <h4>GROWN</h4>
                            </div>
                        </div>
                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                            <div class="main-stat">
                                <h3 id="plants-available"></h3>
                                <h3 id="plants-available-lp"></h3>
                                <h3 id="plants-available-value"></h3>
                                <h4>AVAILABLE</h4>
                            </div>
                        </div>

                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12">
                            <div class="main-stat">
                                <h3 id="plants-daily"></h3>
                                <h3 id="plants-daily-lp"></h3>
                                <h3 id="plants-daily-value"></h3>
                                <h4>DAILY</h4>
                            </div>
                        </div>
                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-4">
                            <br>
                            <div class="main-stat">
                                <h3 id="percent-value"></h3>
                                <h4>% VALUE</h4>
                            </div>
                        </div>
                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-4">
                            <br>
                            <div class="main-stat">
                                <h3 id="percent-grown"></h3>
                                <h4>% GROWN</h4>
                            </div>
                        </div>
                        <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-4">
                            <br>
                            <div class="main-stat">
                                <h3 id="percent-total"></h3>
                                <h4>% TOTAL</h4>
                            </div>
                        </div>
                        <div class="col-12">
                            <br>
                            <div class="main-stat">
                                <h3 id="ratio"></h3>
                                <h4>RATIO</h4>
                            </div>
                        </div>
                    </div>
                    <div class="box m">
                        <div class="row">
                            <div class="col-12">
                                <div class="main-stat">
                                    <br>
                                    <h3 class="heading">On Claim</h3>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                                <div class="main-stat">
                                    <h3 id="claim-drip"></h3>
                                    <h4>DRIP</h4>
                                </div>
                            </div>
                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                                <div class="main-stat">
                                    <h3 id="claim-busd"></h3>
                                    <h4>BUSD</h4>
                                </div>
                            </div>

                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12">
                                <div class="main-stat">
                                    <h3 id="claim-net"></h3>
                                    <h4>NET VALUE</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="box m">
                        <div class="row">
                            <div class="col-12">
                                <div class="main-stat">
                                    <br>
                                    <h3 class="heading">On Compound</h3>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                                <div class="main-stat">
                                    <h3 id="compound-plants"></h3>
                                    <h4>PLANTS</h4>
                                </div>
                            </div>
                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-6">
                                <div class="main-stat">
                                    <h3 id="compound-value"></h3>
                                    <h4>VALUE</h4>
                                </div>
                            </div>
                            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12">
                                <div class="main-stat">
                                    <h3 id="compound-daily"></h3>
                                    <h4>DAILY</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bubble">
                    <div class="row">
                        <div class="col-12">
                            <div class="main-stat">
                                <h1 class="title">Contract Stats</h1>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12">
                            <div class="main-stat">
                                <h3 id="plants-total"></h3>
                                <h3 id="contract-balance"></h3>
                                <h3 id="contract-balance-value"></h3>
                                <h4>BALANCE</h4>
                            </div>
                        </div>
                    </div>
                    <div class="box m">
                        <br>
                        <div class="row">
                        <div class="col-6">
                            <div class="main-stat">
                                <h3 id="total-drip"></h3>
                                <h4>TOTAL DRIP</h4>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="main-stat">
                                <h3 id="total-busd"></h3>
                                <h4>TOTAL BUSD</h4>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="main-stat">
                                <h3 id="lp-drip"></h3>
                                <h4>DRIP PER LP</h4>
                            </div>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </div>

        <footer class="site-footer">
    <div class="row">
        <div class="col-4">
            <a href="https://t.me/cryptcoop" target="_blank" rel="noopener noreferrer">Copyright &copy; 2022
                        The Crypto Cooperative</a>
        </div>
        <div class="col-2" id="screen-size"></div>
        <div class="col-2">
            <a href="#" target="_blank" rel="noopener noreferrer" id="current-users"></a>
        </div>
        <div class="col-4 text-right">
            <a href="https://t.me/delid4ve" target="_blank" rel="noopener noreferrer">Designed by Delid4ve</a>
        </div>
    </div>
</footer>
    </div>
    <script>
    var w = window.innerWidth;
    var h = window.innerHeight;
    var o
    if (window.innerWidth > window.innerHeight) {
        o = 'Landscape'
    } else {
        o = 'Portrait'
    }
    var x = document.getElementById("screen-size");
    x.innerHTML = "Currently viewing @ " + w + "px (w) x " + h + "px (h) - " + o;
</script>

<script>
    window.addEventListener('resize', function (event) {
        var w = window.innerWidth;
        var h = window.innerHeight;
        var o
        if (window.innerWidth > window.innerHeight) {
            o = 'Landscape'
        } else {
            o = 'Portrait'
        }
        var x = document.getElementById("screen-size");
        x.innerHTML = "Currently viewing @ " + w + "px (w) x " + h + "px (h) - " + o;
    }, true);
</script>


</body>

</html>


[☣Disclaimer](https://app.gitbook.com/o/HV0EygnULxrv5yDITPZB/s/ArhQv79QU66iBHghurnn/\~/changes/76/policies/disclaimer)
