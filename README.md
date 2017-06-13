# Shiny k-means Example

A simple example shiny app, with docker configuration.

The example comes whole cloth from the [RStudio Shiny Gallery](http://shiny.rstudio.com/gallery/kmeans-example.html) and is copyright Joe Cheng <joe@rstudio.com>, published under the MIT license.


## Running the Example

Run:

```bash
sudo docker pull wrathematics/shinykmeans
sudo docker run -i -t -p 80:3838 wrathematics/shinykmeans
```

Alternatively, if you prefer/need to to work with the docker file directly:

1. Copy `Dockerfile` to your machine.
2. cd to the dir containing `Dockerfile`
3. `sudo docker build -t shinykmeans .`
4. `sudo docker run -i -t -p 80:3838 shinykmeans`
