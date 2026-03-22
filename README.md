# [shapefile.io](https://shapefile.io)
> View Shapefiles in the Browser

<img width="358" height="172.5" alt="Screenshot 2026-03-21 at 8 11 14 PM" src="https://github.com/user-attachments/assets/b2bd3241-7c84-4402-883c-8c8f29c3bc41" />

## loading shapefile by upload
Just click and drag your file or click the center to open up a file finder.  
<img width="356" height="172.5" alt="Screenshot 2026-03-21 at 8 16 16 PM" src="https://github.com/user-attachments/assets/e58b023f-f7e4-45aa-832a-f792e5623771" />


## loading shapefile by url
You can share a link that automatically loads a zipped shapefile through the url param:  
https://shapefile.io/?url=https://gocarta.s3.us-east-2.amazonaws.com/public/data/clever_vehicle_locations/v1/data.points.shp.zip

## embedding shapefile.io
You can embed a map of your own shapefile in your own website.  Because this fetches the file in the browser, no server is required.
```html
<iframe src="https://shapefile.io/?url=https://gocarta.s3.us-east-2.amazonaws.com/public/data/clever_vehicle_locations/v1/data.points.shp.zip"></iframe>
```

### support
Email questions to daniel.j.dufour@gmail.com or post an issue [here](https://github.com/DanielJDufour/shapefile.io/issues).
