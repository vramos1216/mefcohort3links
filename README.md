# mefcohort3links
Important links from the class

https://github.com/sureshmelvinsigera/CSC-424-Advanced-Database-Management-Systems/blob/master/Lecture%203%20-%20Introducing%20Psycopg%2C%20and%20CRUD%20using%20Psycopg.pdf
https://github.com/sureshmelvinsigera/CSC-424-Advanced-Database-Management-Systems/blob/master/Lecture%204-%20Introduction%20NOSQL%2C%20and%20MongoDB.pdf
https://builtin.com/data-science/object-relational-mapping
https://www.abstractapi.com/guides/put-vs-patch#:~:text=PUT%20and%20PATCH%20both%20perform,entire%20body%20in%20the%20request.
https://vertabelo.com/blog/vertabelo-tips-good-er-diagram-layout/
https://tomharrisonjr.com/uuid-or-guid-as-primary-keys-be-careful-7b2aa3dcb439
https://blog.supportgroup.com/getting-started-with-relational-databases-one-to-one-and-many-to-many-relationships
https://www.geeksforgeeks.org/express-js-req-query-property/
To ensure that the message "Todo deleted with ID: ${id}" is returned to the client when a TODO item is successfully deleted, you should modify the HTTP status code and how the response is sent. The HTTP 204 No Content status code is used to indicate that the server has successfully fulfilled the request and that there is no additional content to send in the response payload body. Since you want to return a message, using HTTP 200 OK or another suitable status code that indicates success and allows a response body is more appropriate.

https://react.dev/
https://addons.mozilla.org/en-US/firefox/addon/react-devtools/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
https://gist.github.com/sureshmelvinsigera/5ee50981d36be1543acd39f8973a0f38
https://www.codingninjas.com/studio/library/difference-between-npm-and-npx
https://d-9067a8f456.awsapps.com/start#/
https://www.browserstack.com/guide/css-selectors-in-selenium
https://marketplace.visualstudio.com/items?itemName=angelorafael.jsx-html-tags
https://github.com/sureshmelvinsigera/node-calc-api-jenkins-docker
https://git.generalassemb.ly/sureshmelvinsigera/cicd/blob/main/image.png
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html

Command	Explanation
npm init	Initializes a new Node.js project. This command creates a package.json file in your project directory which holds various metadata relevant to the project.
npm install <package_name>	Installs a package locally in your project directory. This command adds the package to the node_modules folder and also updates the package.json and package-lock.json files.
npm install -g <package_name>	Installs a package globally. This is typically used for packages that provide command-line tools.
npm update	Updates all the packages listed to the latest version (according to the semver range declared in package.json).
npm run <script>	Runs a script defined in the package.json's "scripts" field.
npm start	Runs the "start" script in package.json. Commonly used to start a server or application.
npm test	Runs the "test" script in package.json, often used to run test suites.
npm install <package_name> --save-dev	Installs a package as a dev dependency. The package will appear in your devDependencies.
npm uninstall <package_name>	Removes a package from node_modules and your package.json file.
npm cache clean --force	Clears the NPM cache from your computer. Sometimes needed to resolve installation issues.
npm pack	Creates a tarball from a package.
npm ci	Similar to npm install, but it's meant for automated environments and will install dependencies exactly as specified in package-lock.json.
	
sudo service postgresql start	This command is used to start the PostgreSQL service on your system
sudo service postgresql stop	This command is used to stop the PostgreSQL service on your system
sudo service docker start	Similar to the previous command, this one starts the Docker service on your system. Docker must be running to manage containers and images
sudo docker network create todo-app	This Docker command creates a new network named todo-app. Docker networks provide a way for Docker containers to communicate with each other directly and also with the outside world. They can be especially useful in microservices architecture.
sudo docker ps	This command lists all currently running Docker containers. It shows details like container ID, image used, when the container was created, the status, ports, and name
sudo docker ps -a	This command lists all Docker containers, including those that are currently running and those that have stopped. This is useful for seeing a complete history of containers on your system.
sudo docker stop container_id	This command will stop the container that is currently running
sudo docker start container_id	Restarts a previously created and stopped Docker container identified by its container_id.
sudo docker rm -f container_id	This command forcefully removes a Docker container specified by its container_id. The -f flag stands for force, and it ensures that the container is stopped and then removed
sudo docker rmi image_name	This command removes a Docker image from your local storage. image_name is the name of the image you want to remove. Images are templates used to create containers and are stored locally once pulled from a registry like Docker Hub.
sudo docker inspect image-name	This command displays detailed information in JSON format about a Docker image specified by image-name. It includes information like the image's layers, tags, and configuration details.
sudo docker logs container_id	This command fetches the logs of a Docker container. It's useful for debugging and understanding the behavior of applications running inside containers.
sudo docker network ls	Lists all networks created in Docker on your system. This can include default networks like bridge, host, and none, along with any custom networks you've created.
sudo docker network rm network_name	Removes a Docker network specified by network_name. Containers must be disconnected from the network before it can be removed
sudo docker image prune --all --force	Remove all the docker images
	
sudo kill -9 $(sudo lsof -t -i:3000)	If the port is running it will kill given port number, or else throws an error saying not enough arguments.
/opt/Postman/app/Postman	Open Postman application.
	
git rm -r --cached .	
git reset --soft HEAD~1	
