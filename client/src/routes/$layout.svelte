<script>
    import Header from './../lib/base/header/Header.svelte';
    import Footer from './../lib/base/footer/Footer.svelte';
    import '../static/style/scss.svelte';
</script>


<div class="wrapper">
    <div class="header">
        <Header/>
    </div>

    <div class="content">
        <slot/>
    </div>

    <div class="footer">
        <Footer/>
    </div>
</div>

