# Codes de suivi — annexes.13080.fr

Toute nouvelle page HTML de ce dépôt doit inclure les deux codes de suivi ci-dessous, à coller juste avant la balise `</head>`.

> Statut : en attente. Ces codes ne sont pas encore ajoutés aux pages existantes (`404.html`, `2026/12/avent.html`). On les utilise sur les prochaines pages.

## Microsoft Clarity

ID du projet : `zhc2r5871f`

```html
<script type="text/javascript">
    (function(c,l,a,r,i,t,y){
        c[a]=c[a]||function(){(c[a].q=c[a].q||[]).push(arguments)};
        t=l.createElement(r);t.async=1;t.src="https://www.clarity.ms/tag/"+i;
        y=l.getElementsByTagName(r)[0];y.parentNode.insertBefore(t,y);
    })(window, document, "clarity", "script", "zhc2r5871f");
</script>
```

## Matomo

Serveur : `https://vigie.siweb.13080.fr/` · ID du site : `21`

```html
<!-- Matomo -->
<script>
  var _paq = window._paq = window._paq || [];
  /* tracker methods like "setCustomDimension" should be called before "trackPageView" */
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="https://vigie.siweb.13080.fr/";
    _paq.push(['setTrackerUrl', u+'matomo.php']);
    _paq.push(['setSiteId', '21']);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.async=true; g.src=u+'matomo.js'; s.parentNode.insertBefore(g,s);
  })();
</script>
<!-- End Matomo Code -->
```
