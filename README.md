# HomeScopeCA

HomeScopeCA is a web application that uses MindsDB AI & Node.js to predict or forecast house prices in California. The prediction is based on the trained machine-learning model developed using historical data on house prices in California. 

HomeScopeCA is a powerful web application that can provide valuable insights to anyone who is interested in buying & selling property in California. 

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Installation

Steps to run app on localhost

Step 1] Clone the project from github:   
```bash
  git clone https://github.com/bakkeshks/HomeScopeCA.git
```
Step 2] Install the dependencies:
```bash
  npm install
```
Step 3] Install the latest version of MindsDB Docker Image & run the docker:
```bash
  docker pull mindsdb/mindsdb
  sudo systemctl start docker
```
Step 4] Download the dataset from kaggle: 
```bash
https://www.kaggle.com/datasets/camnugent/california-housing-prices
```
Step 5] Go to http://localhost:47334 & select the option to upload the data through files (.csv).

Step 6] Import the housing.csv & give home_table as the name of the table in the datasource name field.

Step 7] After you press save , it will import data to files database and it had created home_table in the files. 

Step 8] Once table is created , you have to create & train the model with the data.

Step 9] Now you can write the query & predit the value in the mindsdb editor.

Step 10] Start the node.js server on your machine:
```bash
node app.js 
```
