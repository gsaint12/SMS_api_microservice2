# Use a lighter version of Node as a parent imageFROM mhart/alpine-node:8.11.4
# Set the working directory to /apiWORKDIR /api
# copy package.json into the container at /apiCOPY package*.json /api/
# install dependenciesRUN npm install
# Copy the current directory contents into the container at /apiCOPY . /api/
# Make port 80 available to the world outside this containerEXPOSE 80
# Run the app when the container launchesCMD ["npm", "start"]
