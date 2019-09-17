<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link href="https://fonts.googleapis.com/css?family=Lato:400,900&amp;display=swap" rel="stylesheet">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <title>QUOTE GENERATOR</title>
</head>

<style>
    .main-container {
        min-height: 100vh;
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        padding: 15px;
    }

    #bg-image {
        position: fixed;
        top: 0px;
        left: 0px;
        right: 0px;
        bottom: 0px;
        z-index: -1;
        background: url("https://source.unsplash.com/random/1920x1080");
        background-size: cover !important;
        background-position: top center !important;
        background-repeat: no-repeat !important;
    }

    .quote-content {
        display: none;
    }

    .quote-content p {
        font-size: 32px;
        font-weight: bold;
        color: #ffffff;
        text-shadow: 1px 1px 4px #333333;
        max-width: 90%;
        margin: 0 auto;
        font-family: 'Lato', sans-serif;
    }

    .person {
        font-size: 25px;
        font-style: italic;
        color: #ffffff;
        text-shadow: 1px 1px 4px #333333;
        display: none;
        margin-bottom: 40px;
    }

    #get-quote,
    #get-photo {
        background: #FFF;
        border: 0px;
        padding: 6px 20px;
        border-radius: 6px;
        display: none;
        font-weight: bold;
        color: #4c4c4c;
        cursor: pointer;
        outline: none;
        display: inline-block;
        margin: 10px;
    }
</style>

<body>
    <main class="container-fluid text-center main-container">

        <div id="bg-image"></div>

        <div id="box">
            <p class="quote-content"></p>
            <p class="person"></p>
        </div>

        <button id="get-quote">REFRESH QUOTE</button>
        <button id="get-photo">REFRESH PHOTO</button>

    </main>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"
        integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>

    <!-- jquery -->
    <script type="text/javascript">

        //initialize
        function initialize() {
            $.ajax({
                url: 'https://quotesondesign.com/wp-json/wp/v2/posts/?orderby=rand',
                dataType: 'json',
                success: function (data) {
                    var post = data.shift();
                    console.log(post);
                    alert('asd');
                    $('.quote-content').html(post.content.rendered).fadeIn(1000);
                    $('.person').text(post.title.rendered).fadeIn(1500);
                },
                error: function() {
                    alert('ERROR');
                }
            });
        };

        $(document).ready(function() {

            $('#bg-image').fadeIn(500);
            $('#get-quote, #get-photo').fadeIn(1500);
            initialize();

            //get quote
            $('#get-quote').on('click', function (e) {
                e.preventDefault();

                $.ajax({
                    url: 'https://quotesondesign.com/wp-json/wp/v2/posts/?orderby=rand',
                    dataType: 'json',
                    success: function (data) {

                        var post = data.shift();
                        console.log(post);
                        $('.quote-content').html(post.content.rendered).hide().fadeIn(1000);
                        $('.person').text(post.title.rendered).hide().fadeIn(1500);

                    },
                    error: function() {
                        alert('ERROR');
                    },
                    cache: false
                });
            });

            //unsplash
            $('#get-photo').on('click', function (e) {
                e.preventDefault();

                $.ajax({
                    url: 'https://api.unsplash.com/photos/random/?client_id=aa8445146aa1fb8bc55beecba03e4cee3f630ba73cc020862e0da7e74f28429d',
                    dataType: 'json',
                    success: function (photo) {
                        console.log(photo);
                        $('#bg-image').hide().css('background', 'url(' + photo.urls.regular + ')').fadeIn(1500);
                    },
                    error: function() {
                        alert('ERROR');
                    }
                });
            });
        });



    </script>

</body>

</html>