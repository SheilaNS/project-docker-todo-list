FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
COPY package*.json ./
RUN npm install
COPY . .
ADD node_modules.tar.gz ./
CMD ["npm", "test"]
