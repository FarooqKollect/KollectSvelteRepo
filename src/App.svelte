<script>
    import Nav from './layouts/nav.svelte'
    import Aside from './layouts/aside.svelte'
    import Content from './layouts/contents.svelte'
	export let name;
</script>
 <Aside />
<main class="main-content position-relative max-height-vh-100 h-100 border-radius-lg">
   
    <Nav />
    <Content />
</main>


