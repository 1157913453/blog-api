<template>
<head>
  ..
  <script src="//cdn.jsdelivr.net/npm/@waline/client"></script>
  ...
</head>
<body>
  ...
  <div id="waline"></div>
  <script>
    Waline({
      el: '#waline',
      serverURL: 'https://blog-api-fpradoytl-1157913453.vercel.app/',
    });
  </script>
</body>
  <Tutorial/>
</template>
