<script>
	import '../app.css';
</script>
<body class="flex flex-col h-screen">
<header class="bg-primary text-white p-2 flex ">
    <a href="./" >
    <h1 class="text-3xl mr-10 "> Administration Sirius Coop</h1>
    </a>
<nav class="flex gap-x-4">
    <a href="./contrat" >
        <button class="bg-white text-secondary  rounded p-2">  Contrat</button>
    </a>
    <a href="./devis">
    <button class="bg-white text-secondary rounded p-2">  Devis</button>
</a>
</nav>
   </header>
   <main class="bg-gradient-to-r  flex-grow from-secondary to-third py-10">

  
  <slot></slot>
  </main>
</body>