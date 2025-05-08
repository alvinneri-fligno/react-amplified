# React Notes App with AWS Amplify

This is a simple notes application built with React and AWS Amplify.

## Development Mode

The application is currently running in development mode without actual AWS services. This allows you to develop and test the UI without needing to configure AWS resources.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm run dev
   ```

3. Open your browser at the URL shown in the terminal (typically http://localhost:5173)

## Features

- User authentication (simulated in development mode)
- Create, read, and delete notes
- Upload images for notes (simulated in development mode)

## Deploying with AWS Amplify

To deploy this application with real AWS services:

1. Install the AWS Amplify CLI:
   ```
   npm install -g @aws-amplify/cli
   ```

2. Configure the Amplify CLI:
   ```
   amplify configure
   ```

3. Initialize Amplify in your project:
   ```
   amplify init
   ```

4. Add authentication:
   ```
   amplify add auth
   ```

5. Add API (GraphQL):
   ```
   amplify add api
   ```

6. Add storage:
   ```
   amplify add storage
   ```

7. Push your changes to AWS:
   ```
   amplify push
   ```

8. Update the code to use the real Amplify configuration.

## Troubleshooting

If you encounter issues with AWS Amplify:

1. Make sure your AWS credentials are properly configured
2. Check that you have the necessary permissions
3. Verify that your Amplify configuration is correct
4. Run `amplify status` to check the status of your Amplify project