<script>
    import '$lib/css/global.css';
    import Header from '$lib/components/header/Header.svelte';
    import Footer from '$lib/components/footer/Footer.svelte';
    
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,400;0,600;0,900;1,700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/af77942d5c.js" crossorigin="anonymous"></script>
</svelte:head>

<Header title="This is my title as a prop"/>
<!-- <h1>Welcome to my website</h1> -->

<slot></slot>

<div id="footer">
    <Footer />
</div>

<style>
    #footer {
        background-color: var(--bg-header);
    }
</style>