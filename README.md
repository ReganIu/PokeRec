PokeRec is a Pokemon Card recognition app to collectible card game hobbyists who would like to get more details on their collection! 

Axios was used to make API calls to an unofficial Pokemon card catalogue, which also allowed us to determine the value of cards. Images are stored in an S3 bucket after being sent through AWS's API Gateway and Lambda Functions. The AWS Rekognition machine learning model was also used recognize specific features/icons that show up on the cards. The front-end was designed using React-Native as well.
