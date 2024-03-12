# insurance
use ussd to present an assessment of risk for insurance companies. This then states whether you merit for the insurance
1. Install the dependencies using npm install
2. Change the .env.example file to .env and add your Africa's Talking API Key and username
3. Run the application using npm start or npm run dev for development
4. The application will be running on http://localhost:3000
5. Use a tool like ngrok or localtunnel to expose the application to the internet
6. You can now use the exposed URL to configure the USSD application on Africa's Talking
7. The entry point for the USSD application is http://<exposed-url>/ussd
