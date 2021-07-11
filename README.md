# AG Grid Community Repackaged for Django

[AG Grid Community](https://ag-grid.com/) packaged in a Django reusable app.


## Installation

    pip install django-js-lib-ag-grid-community

## Usage

1. Add `"js_lib_ag_grid_community"` to your `INSTALLED_APPS` setting like this::

       INSTALLED_APPS = [
           ...
           "js_lib_ag_grid_community",
           ...
       ]

2. In your template use:
   
       {% load static %}
   
      and one of:
    
       <script src="{% static "ag_grid_community/ag-grid-community.js" %}"></script>
       <script src="{% static "ag_grid_community/ag-grid-community.min.js" %}"></script>
       <script src="{% static "ag_grid_community/ag-grid-community.noStyle.js" %}"></script>
       <script src="{% static "ag_grid_community/ag-grid-community.min.noStyle.js" %}"></script>

