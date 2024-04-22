# Step 1: Specify the base image
FROM node:18-alpine

# Step 2: Set the working directory
WORKDIR /app

# Step 3: Copy package.json and package-lock.json
COPY package*.json ./

# Step 4: Install dependencies
RUN npm install --production

# Step 5: Copy the rest of your application
COPY . .

# Step 6: Build the Next.js application
RUN npm run build

# Step 7: Specify the command to start the application
CMD ["npm", "start"]