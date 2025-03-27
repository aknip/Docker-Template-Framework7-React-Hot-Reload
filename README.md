# Framework7 React - Kitchen Sink

- docker-compose up
- http://localhost:5173

- Sources: frontend/kitchen-sink/react
- Supports hot reload


### Execute commands inside Docker
- Use `run` for a single one-off execution and starting a container.
- Use `exec` for executing a command in a running container.
Examples => XXX is Docker container name / service name:
- docker-compose run XXX bash
- docker-compose run XXX python3 --version
- docker-compose exec XXX bash
- docker-compose exec XXX python src/marimoapp.py

### Notes
- https://framework7.io/react/kitchen-sink
- https://github.com/framework7io/framework7/
- Changes:
  - package.json: "react": "npm run ... \"vite kitchen-sink/react --host\" => --host added to expose port 5173

