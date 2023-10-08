# References
[Containerize Python Applications with Docker](https://www.youtube.com/watch?v=0TFWtfFY87U)

### Build a container
```bash
docker build -t <YOUR_CONTAINER_NAME> .
```
### Run the container at a specific port
```bash
docker run -p 9999:9999 <YOUR_CONTAINER_NAME>
```