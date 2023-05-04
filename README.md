# **Kedro Data Science**

Kedro is an unopinionated Data Engineering framework that comes with a somewhat opinionated template. It gives the user a way to build pipelines that automatically take care of io through the use of abstract DataSets that the user specifies through Catalog entries. These Catalog entries are loaded, ran through a function, and saved by Nodes. 
The order that these Nodes are executed are determined by the Pipeline, which is a DAG. It's the runner's job to manage the execution of the Nodes

![](https://i0.wp.com/neptune.ai/wp-content/uploads/2022/10/Building-and-Managing-Data-Science-Pipelines-with-Kedro2.png?resize=817%2C319&ssl=1)
