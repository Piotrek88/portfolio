# Analiza EDA Archiwalnych Danych z JostJoinIT
<br>

* Data utworzenia: 2025-02-17
<br>
Zapraszam do zapoznania się z moją analizą danych historycznych ofert pracy z portalu JustJoin.IT za pomocą eksploracji domenowej (EDA). W tej analizie znajdują się wnioski i ciekawe obserwacje o ofertach pracy. 
<br>
<a href="archive_eda_jjit.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="archive_eda_jjit.html"
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