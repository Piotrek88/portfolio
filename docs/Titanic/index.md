# Analiza EDA Danych Titanic

* Data utworzenia: 2024-09-15

Zapraszam do zapoznania się z moją analizą danych Titanica za pomocą eksploracji domenowej (EDA). W tej analizie znajdują się wnioski i ciekawe obserwacje o ofiarach tej katastrofy. 

<a href="edatitanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="edatitanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>