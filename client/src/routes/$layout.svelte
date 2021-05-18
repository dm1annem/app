<script>
    import Header from './../lib/base/header/Header.svelte';
    import Footer from './../lib/base/footer/Footer.svelte';
    import './../app.postcss'
</script>


<div class="">
    <div class="">
        <Header/>
    </div>

    <div class="">
        <slot/>
    </div>

    <div class="">
        <Footer/>
    </div>
</div>


