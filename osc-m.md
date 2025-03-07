# Open Science Community Maastricht events

Current and past events:

<link rel="stylesheet" property="stylesheet" href="https://elixirtess.github.io/TeSS_widgets/css/tess-widget.css"/>
<div id="tess-widget-events-table" class="tess-widget tess-widget-faceted-table"></div>
<script>
function initTeSSWidgets() {
    TessWidget.Events(document.getElementById('tess-widget-events-table'),
        'FacetedTable',
        {
            opts: {
                columns: [{name: 'Date', field: 'start'},
                    {name: 'Name', field: 'title'},
                    {name: 'Location', field: 'location'}],
                allowedFacets: ['keyword'],
                facetOptionLimit: 5
            },
            params: {
                contentProvider: [ "OSCM", "OSCR", "OSCT", "OSCE", "OSCG", "OSCD" ],
                includeExpired: true,
                sort: late
            },
            baseUrl: 'https://taxila.nl'
        });
}
</script>
<script async="" defer="" src="https://elixirtess.github.io/TeSS_widgets/js/tess-widget-standalone.js" onload="initTeSSWidgets()"></script>
