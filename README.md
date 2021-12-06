<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta charset="UTF-8">
    </head>
    <body>
        <h1 class="header">Companion</h1>
        <p><button type="button" class="b">Full Videos</button></p>
        <p><button type="button"class="b">Segments</button></p>
        <p><button type="button"class="b">About Creator & Software</button></p>
    </body>
</html>
<style>
    body{
        background-image: url("https://image.freepik.com/free-vector/office-wallpaper-video-conferencing_23-2148653947.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        animation-name: backgroundchange;
        animation-iteration-count: infinite;
        animation-duration: 60s;
        animation-delay: 5s;
        animation-timing-function:ease-in-out;
    }
    h1{
        text-align: center;
        color: rgb(126, 58, 58);
        margin-top: 20%;
        font-size: 50px;
    }
    p{
        text-align: center;
        display: inline;
        padding: 5pc;
        margin-left: 12%;
        font-size: 20px;
    }
    .b{
        margin-top: 5%;
        color: rgb(126, 58, 58);
        background-color: inherit;
        height: 50px;
        border-radius: 50px;
    }
    @keyframes backgroundchange{
        30%{background-image: url("https://i.pinimg.com/736x/b3/cd/e2/b3cde218d62d5075aa9e93b5a653f426.jpg");}
        50%{background-image: url("https://media.istockphoto.com/photos/white-office-desk-with-copy-space-open-notebook-keyboard-coffee-and-picture-id1277758901?b=1&k=20&m=1277758901&s=170667a&w=0&h=u_dkWMN7S3d4czXzxM_2YNTXBS3M6FTLb8KEhQ-uCME=");}
    }
</style>
