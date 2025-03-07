# OSC-NL Events

<link rel="stylesheet" property="stylesheet" href="https://elixirtess.github.io/TeSS_widgets/css/tess-widget.css"/>
<div id="tess-widget-google-map" class="tess-widget tess-widget-google-map"></div>
<script>
function initTeSSWidgets() {
    TessWidget.Events(document.getElementById('tess-widget-google-map'),
        'GoogleMap',
        {
            opts: {
                apiKey: 'AIzaSyAtxeshmu-95V4KZWyDklhhO-UNqNQQJKo',
                cluster: true
            },
            params: {
                contentProvider: [ "OSCI", "OSCM", "OSCR", "OSCT", "OSCE", "OSCG", "OSCD" ]
            },  
            baseUrl: 'https://dev.tess.elixir-europe.org'
        });
}
</script>
<script async="" defer="" src="https://elixirtess.github.io/TeSS_widgets/js/tess-widget-standalone.js" onload="initTeSSWidgets()"></script>
