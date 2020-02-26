
# Wirecloud - SmartMaaS 2019 platform

Repository to store and document the visualization in the FIWARE Wirecloud component for the SmaartMaaS 2019 platform [https://dashboards.2019.smartmaas.services](https://dashboards.2019.smartmaas.services).

Four workspaces for the area of Kiel were visualized and open to the public:

* [Starting page](https://dashboards.2019.smartmaas.services/wirecloud/home)
* [Kiel - Air Quality](https://dashboards.2019.smartmaas.services/smartPredator/kiel-air-quality)
* [Kiel - Traffic & Parking](https://dashboards.2019.smartmaas.services/smartPredator/kiel-traffic-parking)
* [Kiel - Weather](https://dashboards.2019.smartmaas.services/smartPredator/kiel-weather)
* [Kiel - Fuel](https://dashboards.2019.smartmaas.services/smartPredator/kiel-fuel?mode=embedded&theme=wirecloud.defaulttheme)

The widgets directory contains the operators and widgets that were used to implement and visualize the individual dashboards.

> Please note that some of the operators were **specially** adapted for the implementation and visualization of the open source data for Kiel. 
> For your own purposes please use the opators and widgets from the links below. 

## Operators and Widgets:

### Data acquisition
* [NGSI Source Operator](https://github.com/wirecloud-fiware/ngsi-source-operator)
* [QuantumLeap Source Operator](https://github.com/Ficodes/quantumleap-source-operator)

### Data manipulation

##### Filter
* [Value List Filter Operator](https://github.com/Wirecloud/value-list-filter-operator)
* [Value Filter Operator](https://github.com/Wirecloud/value-filter-operator)

##### List Operation and statistics
* [Agile Dashboard Components](https://github.com/Wirecloud/agile-dashboards)
* [Calculator List Operator](https://github.com/lets-fiware/calculator-list-operator)

### Data model adapter (preparation of visualization)

##### Map data model adapter
* [NGSI Entity TO POI Operator](https://github.com/wirecloud-fiware/ngsi-entity2poi-operator)
* [NGSI Datamodel TO POI Operator](https://github.com/wirecloud-fiware/ngsi-datamodel2poi-operator)

##### Graph data model adapter
* [Gauge Chart Generator Operator](https://github.com/Wirecloud/gauge-chart-generator-operator)
* [QuantumLeap 2 Echart Operator](https://github.com/Ficodes/quantumleap-2-echart-operator)
* [Agile Dashboard Components](https://github.com/Wirecloud/agile-dashboards)

### Visualization

##### NGSI data
* [NGSI Browser Widget](https://github.com/wirecloud-fiware/ngsi-browser-widget)

##### Map
* [Openlayers 3 Map Widget](https://github.com/Wirecloud/ol3-map-widget)

##### Charts
* [Highcharts Widget](https://github.com/Wirecloud/highcharts-widget)
* [Echarts Widget](https://github.com/Wirecloud/echarts-widget)
* [Agile Dashboard Components](https://github.com/Wirecloud/agile-dashboards)

##### Editor
* [Markdown Editor Widget](https://github.com/Wirecloud/markdown-editor-widget)
* [JSON Editor Widget](https://github.com/Wirecloud/json-editor-widget)

##### Viewer
* [Markdown Viewer Widget](https://github.com/Wirecloud/markdown-viewer-widget)
* [Workspace Browser Widget](https://github.com/Wirecloud/workspace-browser-widget)












