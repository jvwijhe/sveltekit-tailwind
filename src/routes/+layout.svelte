<script>
  import "../../src/style/app.css";
  let site_name = 'Sveltekit Tailwind';
  let title = 'Sveltekit Tailwind';
  let description = `Sveltekit Tailwind is a boilerplate for Sveltekit with Tailwind CSS and PurgeCSS.`;
  let website = 'https://www.jvw.dev';

  let image = '/veesion-how-it-works-schema.jpeg';
</script>

<svelte:head>
  <title>{title}</title>
<meta
    name="robots"
    content="index, follow"
  /><meta
    name="author"
    content={website}
  /><meta
    name="apple-mobile-web-app-title"
    content={title}
  /><meta
    name="apple-mobile-web-app-status-bar-style"
    content="black"
  /><meta
    property="og:locale"
    content="nl_NL"
  /><meta
    property="og:type"
    content="website"
  /><meta
    property="og:url"
    content={website}
  /><meta
    property="og:site_name"
    content={site_name}
  />

  <meta
    name="description"
    content={description}

  />

  <meta
    property="og:title"
    content={title}
 
  />

  <meta
    property="og:description"
    content={description}
  />


  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200;400;600;700&display=swap"
    rel="stylesheet"
  />

 
</svelte:head>

<header class="">
  <div class="container mx-auto">
   <span>header</span>
  </div>
</header>

<slot />

<footer class="">
  <div class="container mx-auto">
    <span>footer</span>
  </div>
  </footer>