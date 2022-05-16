# Leslie Fleming - Final Project, 2022

## <font style="color:yellow">Synopsis</font>
> Being a sports shooter (clay shooting only), I partake in various events local and troughout the country. During one event, I noticed that the processing of the results was primarily based on manual effort. I thought to myself, hey why not follow Trevor's guidance and learn how to improve the process for the better by means of objection character recognition leveraging Amazon Textract.

## <font style="color:yellow">Requirements </font>

> <table border=1 bordercolor="grey"><b>Final Project 2002</b><br/>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Release</td><td style="border-color:grey; width: 25em">1.0.0</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Epic</td><td style="border-color:grey; width: 25em">n/a</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Document Status</td><td style="border-color:grey; width: 25em">Draft</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Designer</td><td style="border-color:grey; width: 25em">Les Fleming</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Developer</td><td style="border-color:grey; width: 25em">Les Fleming</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">QA</td><td style="border-color:grey; width: 25em">Les Fleming</td></tr>
>   <tr><td style="border-width:1;border-color:grey;background-color: grey">Date</td><td style="border-color:grey; width: 25em">05/16/2022</td></tr>
>  </table>
> <br/>
> <table border=1 bordercolor="grey"><b>Final Project 2002</b><br/>
>   <th style="background-color: grey">#</th>
>   <th style="background-color: grey">User Story Title</th>
>   <th style="background-color: grey">User Story Description</th>
>   <th style="background-color: grey">Priority</th>
>   <th style="background-color: grey">Notes</th>
>   <tr><td>1</td><td>Image Capture</td><td>A user captures an image of the score card with their cell phone</td><td>Must Have</td><td>To be tested with iOS / Android</td></tr>
>   <tr><td>2</td><td>Image Upload</td><td>A user will upload the image to an repository </td><td>Must Have</td><td>Possible Solutions: S3 Bucket or MariaDB</td></tr>
>   <tr><td>3</td><td>Image Processing</td><td>A service will scan for new image upload(s)</td><td>Must Have</td><td></td></tr>
>   <tr><td>4</td><td>Image Textract</td><td>A service will extract text from an image and process the resulting dataset into a storage repository</td><td>Must Have</td><td>Storage repository to be decided on</td></tr>
>   <tr><td>5</td><td>Textract Result</td><td>A user an view the textract result(s) via a website</td><td>Must Have</td><td>User must have an option to select / filter on event</td></tr>
</table>



```html
    this is a test
```


<!--
    link(s) for displaying plantUml in Github
-->
> ![image-capture](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/Les-Linux/com.elbicon.coderscampus.project/main/clsg/src/main/resources/markdown/plantuml/uc-ScorecardImageCapture.puml)

