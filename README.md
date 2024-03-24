# Image Processing Microservice on AWS
Design and deploy scalable, extendable, and maintainable full stack applications using modern cloud architecture.
## Development Server

### Criteria

- **MEETS SPECIFICATIONS**

    - The project demonstrates a working NodeJS service.
    
    - Starting the server with `npm run start` runs a local instance of the server with no errors.
    
    - The project demonstrates RESTful design principles.
    
    - The project demonstrates an appropriate use of HTTP status codes.
    
        - Successful responses have a `200` code, at least one error code for caught errors (i.e. `422`).

## Elastic Beanstalk Deployment

### Criteria

- **MEETS SPECIFICATIONS**

    - The project uses AWS Elastic Beanstalk’s CLI and Console Dashboard.
    
    - The project was deployed using the AWS Elastic Beanstalk CLI `eb init`, `eb create`, and `eb deploy` commands.
    
    - A screenshot of the elastic beanstalk application dashboard is included in a `deployment_screenshot` directory.
    
    - The project includes functional cloud deployments.
    
        - An endpoint URL for a running elastic beanstalk deployment (`EB_URL`) has been submitted along with the project submission. This endpoint responds to valid GET requests.
