# drone-ci-demo

1. Create `.env` file, paste the code below:
  ```bash
  GITHUB_CLIENT_ID=     # Github client ID
  GITHUB_CLIENT_SECRET= # Github client secret
  DRONE_DATA=./drone    # Volume mapping path
  DRONE_SERVER_HOST=    # Ngrok Domain name
  ADMIN=                # your github username
  DRONE_RPC_SECRET=     # Random secret key
  ```
2. Create an empty folder named "drone".
3. You can check [this article](https://yujustcoding.com/step-by-step/devops-drone-ci.html) for a detailed tutorial.
