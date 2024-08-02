<script>
import Form from './lib/form.svelte';
import './app.css'
</script>


<main>
    <section>
        <div class="text__container">
            <h1 class="main__header">CONTACT</h1>
            <h2 class="main__header-text">Reach Out To Us</h2>
        </div>
        <div class="container">
            <Form/>
        </div>

        
    </section>
    
</main>


<style>
    section{
        display: flex;
        flex-direction: row;
        background-color: azure;
    }
    .main__header-text{
        font-size: 48px;
    }

    .text__container{
        width: 50%;
        display: flex;
        justify-content: center;
        background-color: rgb(0, 132, 255);
        align-items: center;
        flex-direction: column;

    }
    .container{
        background-color: black;
        width: 50%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
</style>