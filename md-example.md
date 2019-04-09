---
layout: page
title: Markdown-based page example
subtitle: Subtitle goes here
bigimg: /img/start.jpg
---

## Here is where we can insert an image:

![GW Data Science logo](/img/gwdsp.png)

## How about a link?

And of course some text, and maybe [a link to https://datasci.columbian.gwu.edu/](https://datasci.columbian.gwu.edu/)

## Or some code?

Some code might go here:

```
x <- 5 # Here's some R code
```

What if I just paste the HTML for a plotly plot?

            
        
        <div id="6623df0d-c52f-4d6c-a27f-850fe0e87975" style="width: 100%; height: 100%;" class="plotly-graph-div"></div>
        <script type="text/javascript">
            (function(){
                window.PLOTLYENV={'BASE_URL': 'https://plot.ly'};

                var gd = document.getElementById('6623df0d-c52f-4d6c-a27f-850fe0e87975')
                var resizeDebounce = null;

                function resizePlot() {
                    var bb = gd.getBoundingClientRect();
                    Plotly.relayout(gd, {
                        width: bb.width,
                        height: bb.height
                    });
                }

                

                
                Plotly.plot(gd, {
                    data: [{"uid": "55f8e689-7a76-46be-ac7e-872159fc3024", "type": "bar", "xsrc": "kerchner:3:3969a8", "x": ["MIT", "Stanford", "Harvard", "U.Penn", "Princeton", "Chicago", "Georgetown", "Tufts", "Yale", "Columbia", "Duke", "Dartmouth", "NYU", "Notre Dame", "Cornell", "Michigan", "Brown", "Berkeley", "Emory", "UCLA", "SoCal"], "ysrc": "kerchner:3:f12442", "y": [58, 55, 53, 49, 47, 40, 37, 36, 35, 33, 31, 30, 27, 27, 27, 22, 20, 17, 14, 14, 9]}],
                    layout: {},
                    frames: [],
                    config: {"showLink": true, "linkText": "Export to plot.ly", "mapboxAccessToken": "pk.eyJ1IjoiY2hyaWRkeXAiLCJhIjoiY2lxMnVvdm5iMDA4dnhsbTQ5aHJzcGs0MyJ9.X9o_rzNLNesDxdra4neC_A"}
                });
                
           }());
        </script>