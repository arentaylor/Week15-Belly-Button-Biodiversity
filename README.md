# Belly Button Biodiversity

https://art-bbb.herokuapp.com/

# Belly Button Biodiversity

![Bacteria by filterforge.com](./static/images/bacteria.jpg)

[Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

Use Plotly.js to build interactive charts for your dashboard.

* Create a PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.

* Create a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

* Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object somewhere on the page

* Update all of the plots any time that a new sample is selected.

## Step 2 - Heroku

Deploy your Flask app to Heroku.

https://art-bbb.herokuapp.com/