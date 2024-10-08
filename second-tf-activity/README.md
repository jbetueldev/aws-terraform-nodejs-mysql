## AWS with Terraform Sample

Create an AWS environment, together with its infrastructure resources (e.g. VPC, subnets, EC2 Instances) using Terraform as IaC.

## Setup

Install Terraform (refer to the lni)


```bash
npm install
```

To run express server locally, run the following:

```bash
npm run start
```

App should be accessible here: [http://localhost:3000](http://localhost:3000).


## Build the application ready for production

Step 1: Install the npm packages
```bash
npm install
```

Step 2: Build the application by running this command
```bash
npm run build-prod
```

Step 3: Run the output build
```bash
npm run serve
```

> NOTE: Before running the application make sure that you have a MySQL VM or container running locally to avoid errors.
