# prediction

## SET-UP

1. **Unzip the Project**:
   Unzip the project files to your desired location.

2. **Start container**:
   Navigate to app directory and start container
   ```bash
   docker-compose up --build

3. **Open Insomnia**
  - create
  - Type = POST
  - url: http://127.0.0.1:5000/predict
  - body --> JSON --> {"tv": 150.0, "radio": 23.0, "newspaper": 12.0}
  - header: click on add --> Header: Contant-Type && value: application/json
  - click on "SEND"
