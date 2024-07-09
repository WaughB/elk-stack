# Elastic training
Just some practice for setting up a basic, local ELK stack. 

## How to run
Go to the root directory and run `docker-compose up`.

## Verify setup
__Elastic__ Open your web browser and navigate to http://localhost:9200. You should see a JSON response indicating that Elasticsearch is running.

__Kibana__ Open your web browser and navigate to http://localhost:5601. This should bring up the Kibana interface.

## Sample problem
Load the sample data from the `/data` directory. This data contains a small amount of information about the Iris dataset. 

Once running, follow the onscreen prompts to the `Upload File` section. Then choose this file and the schema will already be configured for you. I made the index named `test` and used default values for the rest.

After playing around in Lens briefly, I was able to create the dashboard below: 
![](/imgs/petal-dash.png)