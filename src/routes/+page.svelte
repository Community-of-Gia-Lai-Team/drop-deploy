<script>
    import './static/css/main.css';
</script>

<svelte:head>
    <title>Dropage</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</svelte:head>

<section>
    <div class="wrapper">
        <div class="row">
            <div class="image"><img src="https://lanyard.rest/576422773694660608.png" alt=""></div>
            <div class="content">
                <h1>DROPAGE</h1>
                <p><a href="mailto:dropagets@gmail.com">> dropagets@gmail.com</a></p>
                <center><hr class="line"></center>
                <!-- <div class="social-box">
                    <div class="social-links">
                        <li><a href="https://github.com/dropage" target="_blank"><i class="fa-brands fa-github"></i></a></li>
                        <li><a href="https://facebook.com/2006in" target="_blank"><i class="fa-brands fa-facebook"></i></a></li>
                    </div>
                </div> -->
            </div>
        </div>
    </div>
</section>

<style>
    .content {
        color: #fff;
    }
    .row {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    /* .image {
        background: red;
    } */
    .image img {
        width: 200px;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        vertical-align: center;
    }
    .content {
        margin-top: 0.5rem;
        text-align: center;
    }
    .content h1 {
        font-size: 40px;
    }
    .content a {
        color: #fff;
    }
    .content a:hover {
        text-decoration: underline;
    }
    hr.line {
        margin: 1rem 0;
        border: none;
        background: #fff;
        height: 5px;
        opacity: 0.25;
        width: 50px;
        border-radius: 10px;
    }
    /* .social-box {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .social-links {
        display: flex;
        justify-content: center;
        align-items: center;
        display: inline;
    }
    .social-links li {
        display: inline;
    }
    .social-links li a {
        text-align: center;
        color: #e5e5e5;
    }
    .social-links li a:hover {
        color: #fff;
    } */
</style>