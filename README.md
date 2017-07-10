# SwaggerCodeGeneratorInAngular2
This repo contains the customised code for swagger code generation in angular2 and angular4.

# Set up environment for generating the swagger client
- run command 'npm install angular2-swagger-client-generator' to install package required


# Updating swagger client
- If you want to create code from Json file, then add swagger.json to this folder. Update swagger json with latest json text
- open command prompt from directory where to generate the swagger client
- run command 'node a2apigen -s ./swagger.json -o ./'
- it will generate necessary models and swagger client in current folder

-if you want to create model from some swagger docs url, then use the following command:
node a2apigen -u httpUrl -o ./
