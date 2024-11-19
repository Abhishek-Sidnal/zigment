# 🌟 Dynamic Form Generator

A React-based application that allows you to create dynamic forms by defining a JSON schema. Edit, preview, and deploy forms instantly using this intuitive tool.

## 🚀 Features

- **Live JSON Editor**: Edit your JSON schema in real-time with validation feedback.
- **Dynamic Form Generation**: Generate forms instantly based on the schema.
- **Dark Mode Support**: Seamless light and dark mode toggle.
- **JSON Management**: Download or copy the JSON schema for reuse.
- **Field Validation**: Schema validation ensures proper field definitions.
- **Field Support**: Includes text, email, select, radio, checkbox, textarea, and more.

## 🛠️ Technologies Used

- **Frontend**: React.js, Tailwind CSS, React Hook Form
- **State Management**: React State Hooks
- **JSON Validation**: Built-in error detection
- **Deployment**: Vercel

## 🧑‍💻 Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (or yarn)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/dynamic-form-generator.git
    cd dynamic-form-generator
    ```

2. **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Start the development server:**

    ```bash
    npm start
    # or
    yarn start
    ```

4. Open your browser and navigate to:

    ```
    http://localhost:3000
    ```

### JSON Schema Examples

#### **Registration Form**
```json
{
  "formTitle": "User Registration Form",
  "formDescription": "Fill in your details below.",
  "fields": [
    { "label": "Name", "type": "text", "id": "name", "required": true },
    { "label": "Email", "type": "email", "id": "email", "required": true },
    { "label": "Gender", "type": "select", "id": "gender", "options": ["Male", "Female", "Other"] }
  ]
}
