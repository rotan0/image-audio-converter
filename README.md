## Installation

To get started with this project, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <your-project-name>
    ```
    (Replace `<your-repository-url>` and `<your-project-name>` with your actual repository details.)

2.  **Install dependencies:**
    ```bash
    npm install
    # or yarn install
    # or pnpm install
    ```

3.  **Set up environment variables:**
    Create a `.env` file in the root of your project and add your Supabase credentials:
    ```
    VITE_SUPABASE_URL="YOUR_SUPABASE_PROJECT_URL"
    VITE_SUPABASE_ANON_KEY="YOUR_SUPABASE_ANON_KEY"
    ```
    (Replace with your actual Supabase project URL and anon key.)

4.  **Run the development server:**
    ```bash
    npm run dev
    # or yarn dev
    # or pnpm dev
    ```
    The application will typically be available at `http://localhost:8080`.

