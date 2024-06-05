---
title: "L01D"
description: ""
---
  <!-- Element to contain animated typing -->
  <span id="element"></span>

  <!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Der Mensch kann zwar tun, was er will, aber er kann nicht wollen, was er will', 'El hombre puede hacer lo que él quiera, pero no quiere lo que él quiere', '- Arthur Schopenhauer'],
        startDelay: 50,
        typeSpeed: 100,
        backSpeed: 50,
        loop: true,
        showCursor: true,
        shuffle: false
  });
  </script>
</body>