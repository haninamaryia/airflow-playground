# Welcome to airflow-playground :D

This is a very simple project designed for you to get familiar with airflow DAG writing :)

## Get started

1 Run the following command to build the image 

```docker build -t playrflow .  ```  
  
  

2 Then start the container

``` docker run --rm -d -p 8080:8080 playrflow ```  
  
  

3 Finally visit `localhost:8080` in your browser and login with login: admin and password: admin

Here you can see a bunch of default airflow dags that are there to show you different Operators.

Click on a dag name and then on <>Code in the UI to see the code of the DAG and read the description ! 

If you want to remove the default Airflow DAGs from the UI, change the following variable in airflow.cfg to False:
```load_examples = True```    

  
  
## Add your own DAGs

You can also see the dag called backfill. This DAG can be found in the dags directory. If you want to add your own dag to the docker image, add them in that same directory, then follow steps 1, 2, 3 again to see them in the Airflow UI!

### Good luck and have fun!

