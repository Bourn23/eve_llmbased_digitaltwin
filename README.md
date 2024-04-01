# EVE - Build LLM-based digital twins

### Prerequisite

-   Install [PNPM](https://pnpm.io/installation)
    ```bash
    npm i -g pnpm
    ```

### Setup

1. Clone the repository

    ```bash
    git clone https://github.com/Bourn23/eve_llmbased_digitaltwin.git
    
    ```

2. Go into repository folder

    ```bash
    cd eve_llmbased_digitaltwin
    ```

3. Install all dependencies of all modules:

    ```bash
    pnpm install
    ```

4. Build all the code:

    ```bash
    pnpm build
    ```

5. Start the app:

    ```bash
    pnpm start
    ```

    You can now access the app on [http://localhost:3000](http://localhost:3000)

6. For development build:

    - Create `.env` file and specify the `VITE_PORT` (refer to `.env.example`) in `packages/ui`
    - Create `.env` file and specify the `PORT` (refer to `.env.example`) in `packages/server`
    - Run

        ```bash
        pnpm dev
        ```

    Any code changes will reload the app automatically on [http://localhost:8080](http://localhost:8080)

###  Acknowledgements
This project heavily relies on reactflow[https://reactflow.dev/] and flowise[https://github.com/FlowiseAI/] projects.