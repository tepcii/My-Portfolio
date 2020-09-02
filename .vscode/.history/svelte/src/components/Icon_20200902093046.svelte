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
        width: 15%;
        height: 15%;
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
</style>
