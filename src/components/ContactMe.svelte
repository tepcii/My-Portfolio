<script>
    // your script goes here
</script>

<div>

    <h2>Contact Me</h2>

    <form action="https://getform.io/f/ce47a733-07af-4500-bb58-d9d5bae2c8b0" method="POST">

        <input type="text" name="name" placeholder="Name">
        <input type="email" name="email" placeholder="Email Address">
        <input type="text" name="message" placeholder="Message">
        <button type="submit">Send</button>

    </form>
</div>

<style>

    div {
        padding: 20px;
        text-align: center;
    }

    h2 {
        color: #BABECC;
        text-shadow: 1px 1px 1px white;
        padding-bottom: 20px;
    }

    button, input {
        border: 0;
        outline: 0;
        font-size: 16px;
        border-radius: 320px;
        padding: 16px;
        margin-top: 10px;
        margin-bottom: 10px;
        background-color: #ebf5fc;
        text-shadow: 1px 1px 0 white;
    }

    input {
        margin-right: 16px/2;
        box-shadow:  inset 9px 9px 16px rgba(0, 0, 0, 0.1), inset -9px -9px 16px rgba(255, 255, 255, 1);
        width: 100%;
        box-sizing: border-box;
        transition: all 0.2s ease-in-out;
        appearance: none;
        -webkit-appearance: none;
    }

    input:focus {
        box-shadow:  inset 1px 1px 2px rgba(0, 0, 0, 0.1), inset -1px -1px 2px rgba(255, 255, 255, 1);
    }

    button {
        color:#61677C;
        font-weight: bold;
        box-shadow: -9px -9px 16px rgba(255, 255, 255, 1),  9px 9px 16px rgba(163, 177, 198, 0.6);
        transition: all 0.2s ease-in-out;
        cursor: pointer;
        font-weight: 600;
    }

    button:hover {
        box-shadow: -2px -2px 5px rgba(255, 255, 255, 1), 2px 2px 5px rgba(0, 0, 0, 0.1);
    }

    button:active {
        box-shadow: inset 1px 1px 2px rgba(0, 0, 0, 0.1), inset -1px -1px 2px rgba(255, 255, 255, 1);
    }

</style>

<!-- markup (zero or more items) goes here -->