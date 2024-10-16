# RAG-Intake-Form
You can test the function locally before deploying by using the Netlify CLI.

Install the Netlify CLI:
npm install -g netlify-cli

Navigate to your project folder and run the following command to serve the site with live functions:
netlify dev

Your serverless functions will be accessible at:
http://localhost:8888/.netlify/functions/hello


#To Deploy to Production use below command

netlify deploy --prod