npm install
npm start

docker build . -t florian_schaechter/florian-schaechter-app:1.0.0
docker run -p 8080:3000 florian_schaechter/florian-schaechter-app:1.0.0