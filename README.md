# Node.js API Status Checker

This Node.js application consists of a server and a simple HTML/JavaScript client. The server checks the status of a PostgreSQL database, and the client displays the status along with downtime information.

## Server

### Prerequisites
- Node.js installed
- Accessible PostgreSQL server
- Modify the database configuration inside back-end/index.js file.

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. **Navigate to the Server Directory:**
    ```bash
    cd your-repo/server
    ```

3. **Install Dependencies:**
    ```bash
    npm install
    ```

4. **Run the Server:**
    ```bash
    node server.js
    ```
    The server will be running on `http://localhost:3000`.

### Usage

1. **Open the front-end HTML file in a Browser:**
    - Open the `front-end/index.html` file in a web browser.

2. **Status Display:**
    - The page displays a status container that checks the connection to the server every second.

3. **Color Indicators:**
    - The container background turns green for a successful connection and red for an error.

4. **Downtime Counter:**
    - The downtime counter updates in case of errors, showing the duration of downtime.
