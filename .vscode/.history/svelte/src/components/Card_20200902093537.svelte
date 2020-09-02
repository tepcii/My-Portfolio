<script>

</script>

<div>
    <slot></slot>
</div>

<style>


    div {
        width: 100%;
        height: 100%;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        border-radius: 10px;
        background: #ebf5fc;
        box-shadow: -2px -2px 5px rgba(255, 255, 255, 1), 9px 9px 16px rgba(163, 177, 198, 0.1);
    }

    @media screen and (max-width: 959px) {
        /* 959px以下に適用されるCSS（タブレット用） */
    }

    @media screen and (max-width: 480px) {
        /* 480px以下に適用されるCSS（スマホ用） */
    }

    @media screen and (min-width: 481px) {
        /* 481px以上に適用されるCSS（タブレット用） */
    }

    @media screen and (min-width: 960px) {
        /* 960px以上に適用されるCSS（PC用） */
        div {
            max-width: 960px;
        }
    }

</style>
