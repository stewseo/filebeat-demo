
Configure Filebeat and filebeat module

- input: filestream

- output.elasticsearch:
    hosts: ["${FILEBEAT_WRITER}"]
    pipeline processors: 
    - geo-location-pipeline
    - timestamp-pipeline, 
    - format businesses id's
 


