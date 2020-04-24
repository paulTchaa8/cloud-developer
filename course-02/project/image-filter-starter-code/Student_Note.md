# Udagram Image Filtering Microservice

For the project intitled **Udagram - Make your Own Instagram**, 
the Github link to my proposal is just here [Github project](https://github.com/paulTchaa8/cloud-developer/tree/master/course-02/project/image-filter-starter-code)
[x] And the endpoint URL to my elastic beanstalk environment is at [image-filter-dev](http://image-filter-dev-dev2.eu-west-2.elasticbeanstalk.com)
[x] the endpoint URL to work on was **/filteredimage** along with a query parameter **image_url** to get access to a public url.
[x] An example of the enpoint working [here](http://image-filter-dev-dev2.eu-west-2.elasticbeanstalk.com/filteredimage?image_url=https://cemaccalculator.000webhostapp.com/vue/images/victoire.jpg)

I had to build a custom async function to make that array of files to delete called **arrayOfFiles()**. Then We just have to pass the 
resulting array as an input for the **deleteLocalFiles()** function to cleanup the old files before filterng a new one. 