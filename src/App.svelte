<script>
// import Nav from './Nav.svelte';
import Form from './lib/form.svelte';
import Button from './lib/button.svelte';
import './app.css'
</script>


<main>
    <section>
        <h1 class="contact__title">Contact</h1>
        <Form/>
    </section>
    
</main>


<style>
    .contact__title{
        color: rgb(0, 132, 255);
    }
    section{
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        margin: 10px;
    }
</style>