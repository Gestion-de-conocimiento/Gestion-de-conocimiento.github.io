---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/axios/0.21.1/axios.min.js" integrity="sha512-bZS47S7sPOxkjU/4Bt0zrhEtWx0y0CRkhEp8IckzK+ltifIIE9EMIMTuT/mEzoIMewUINruDBIR/jJnbguonqQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

<script async src="https://api.countapi.xyz/hit/jorge-arturo-hernandez-almazan.github.io/visits?callback=callbackName"></script>


<h1> Inicio </h1>

<!--<p class="card-text" > Visitas: <img src="https://hitcounter.pythonanywhere.com/count/tag.svg" alt="Hits"> </p>-->



<script src="{{ base.url | prepend: site.url }}/assets/js/main.js"></script>

<table style="width:100%">
  <tr>
    <th>
        <h2> Sistema </h2>

        <p> Archivo:  <span id="archivo"> </span> </p>
        <p> Tamaño: <span id="tamanio"> </span> KB</p>
        <p> Total de descargas:  <span id="descargas"> </span> </p>
        <a class="btn btn-green" href="#" id="btn_descarga_sistema" role="button">Descargar</a>


    </th>

    <th>
        <h2> Documentación </h2>

        <p> Archivo:  <span id="archivo_doc"> </span> </p>
        <p> Tamaño: <span id="tamanio_doc"> </span> KB</p>
        <p> Total de descargas:  <span id="descargas_doc"> </span> </p>
        <a class="btn btn-green" href="#" id="btn_descarga_manual" role="button">Descargar </a>
    </th>

  </tr>

</table>

<p>Total de visitas: <span id="visits"></span> </p>