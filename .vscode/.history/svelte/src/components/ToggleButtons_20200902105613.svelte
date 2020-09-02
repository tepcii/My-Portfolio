<script>
    export let toggle;
</script>

<div>
    <ul class="nav">
        <li on:click={toggle(0)} tabindex="0">About</li>
        <li on:click={toggle(1)} tabindex="0">Contact</li>
    </ul>
</div>

<style>

    ul {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    li {
        list-style-type: none;
        margin: 0 1rem;
        padding: 0.5rem 1.5rem;
        border: 2px solid rgba(255,255,255,.3);
        box-shadow: 4px 4px 6px 0 rgba(0,0,0,.1), -4px -4px 6px rgba(255,255,255,1);
        border-radius: 10px;
        cursor: pointer;
        transition: color 0.2s ease-out, transform 0.2s ease-out;
        color: dimgray;
    }

    li:hover {
        transform: scale(1.05);
        box-shadow: 4px 4px 10px 0 rgba(0,0,0,.1), -4px -4px 10px rgba(255,255,255,1);
    }

    li:focus {
        outline: none;
        transform: scale(0.95);
        box-shadow: 4px 4px 10px 0 rgba(0,0,0,.1), -4px -4px 10px rgba(255,255,255,1), 4px 4px 10px 0 rgba(0,0,0,.1) inset, -4px -4px 10px rgba(255,255,255,1) inset;
    }

    list:hover, list:focus {
        color: orangered;
    }

    @media screen and (max-width: 480px) {
        /* 480px以下に適用されるCSS（スマホ用） */
        div {
            margin-top: 20px;
        }
    }

</style>
