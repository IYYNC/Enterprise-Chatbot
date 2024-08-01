# Enterprise-Chatbot
<h1>Enterprise Chatbot Project</h1>

<h2>Overview</h2>
<p>This project develops an advanced enterprise-level chatbot using OpenAI's RAG (Retrieval-Augmented Generation) technology integrated via API for generating context-aware and knowledgeable responses. The chatbot is capable of writing queries based on user prompts, executing them, and returning dataframes along with basic analysis. Development is streamlined with Azure DevOps, while data storage is managed through Snowflake. The frontend is implemented using Streamlit, providing an interactive user experience.</p>

<h2>Features</h2>
<ul>
    <li><strong>OpenAI RAG Integration</strong>: Uses OpenAI's RAG model to enhance the chatbot's ability to provide accurate and context-aware answers.</li>
    <li><strong>Query Generation</strong>: Capable of interpreting user prompts to generate and execute data queries, returning structured data and insights.</li>
    <li><strong>Azure DevOps</strong>: Utilizes Azure DevOps for continuous integration and continuous delivery, enhancing the development workflow.</li>
    <li><strong>Snowflake Database</strong>: Uses Snowflake for scalable, secure, and efficient data storage.</li>
    <li><strong>Streamlit UI</strong>: Provides a user-friendly interface built with Streamlit, accessible to users with various technical backgrounds.</li>
</ul>

<h2>Getting Started</h2>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h3>Prerequisites</h3>
<ul>
    <li>Azure account</li>
    <li>Snowflake account</li>
    <li>Python 3.8+</li>
    <li>Streamlit</li>
</ul>

<h3>Installation</h3>
<ol>
    <li>Clone the repository:
        <pre>git clone https://github.com/your-username/enterprise-chatbot.git<br>cd enterprise-chatbot</pre>
    </li>
    <li>Install required Python libraries:
        <pre>pip install -r requirements.txt</pre>
    </li>
    <li>Set up environment variables (e.g., SNOWFLAKE_USER, SNOWFLAKE_PASSWORD, OPENAI_API_KEY) in a .env file in the root directory.</li>
</ol>

<h3>Running the Application</h3>
<p>To run the application locally:</p>
<pre>streamlit run app.py</pre>

<h2>Usage</h2>
<p>After launching the application, navigate to the provided localhost URL in your web browser. Interact with the chatbot interface to perform tasks or retrieve information as configured.</p>

<h2>Deployment</h2>
<p>Details on deploying this application in a production environment using Azure.</p>

<h2>Contributing</h2>
<p>We welcome contributions! Please read <code>CONTRIBUTING.md</code> for details on our code of conduct and the process for submitting pull requests to us.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the <code>LICENSE.md</code> file for details.</p>

<h2>Acknowledgments</h2>
<ul>
    <li>Thanks to OpenAI for the API and resources.</li>
    <li>Microsoft Azure DevOps for the CI/CD tools.</li>
    <li>Snowflake for data handling solutions.</li>
</ul>
