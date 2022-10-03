### Configure Filebeat to monitor an input path, Harvest log lines, ship data to an Elasticsearch output to be indexed
- Configure Filebeat Inputs
- Configure Filebeat Outputs

#### Get restaurants in 10,000 meter radius of Twin Peaks Latitude: 37.751586275, Longitude: -122.447721511![image](https://user-images.githubusercontent.com/54422342/193492104-6958ceab-571e-4e75-b1c0-895fbd836508.png)

- curl -H Authorization Bearer $YELP_API_KEY GET https://api.yelp.com/v3/businesses/search?term=restaurants&longitude=-122.4477&latitude=37.7516 &radius=10000&sort_by=distance
- add zipcode request parameter


#### Create dashboards and visualization panels
- Machine Learning: [Anomaly detection, Data frame analytics, AIOps]
- https://www.elastic.co/guide/en/kibana/current/xpack-ml.html


