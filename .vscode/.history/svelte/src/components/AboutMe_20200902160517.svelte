<script>
    import DentedCard from './DentedCard.svelte';
</script>

<div>

    <h2>About Me</h2>

    <DentedCard>
        <div class="description">
            Hi</br>
            I'm a <b>front-end engineer</b>.</br>
            I'm also interested in <b>mobile application development</b> using <b>Flutter</b>.
        </div>
    </DentedCard>

</div>

<style>

    div {
        padding: 20px;
        text-align: center;
        width: 100%;
        height: 100%;
    }

    div.description {
        text-align: left;
    }

    h2 {
        color: #BABECC;
        text-shadow: 1px 1px 1px white;
        padding-bottom: 20px;
    }

</style>
