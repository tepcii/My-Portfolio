<script>
    let src = "img/icon.jpg";
</script>

<div class="trim">
    <img {src} alt="Tepci's Icon">
</div>

<style>
    .trim {
        position: relative;
        overflow: hidden;
        width: 150px;
        height: 150px;
        border-radius: 50%;
    }
    .trim img{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        height:100%;
    }
    div {
        position: absolute;
        top: -75px;
        left: calc(50% - 75px);
        border: 10px solid #ebf5fc;
        border-radius: 10px;
        box-shadow: -9px -9px 16px rgba(255, 255, 255, 1), 9px 9px 16px rgba(163, 177, 198, 0.6);
    }

    @media screen and (max-width: 480px) {
        /* 480px以下に適用されるCSS（スマホ用） */
        div {
            top: 9px;
        }
    }

</style>
