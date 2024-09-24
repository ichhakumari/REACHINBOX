<h1>ReachInbox - Project Documentation</h1>
Project is Live here....
https://startling-tulumba-2cb36c.netlify.app/
<div class="container">
<h2>Introduction</h2>

   <p>Welcome to ReachInbox - a revolutionary AI-driven platform transforming cold outreach. ReachInbox is an all-in-one solution for businesses to effortlessly find, enrich, and engage high-intent leads using multi-channel outreach across Twitter, LinkedIn, email, and phone. With a single prompt, ReachInbox sets in motion prospecting and verifying leads, crafting personalized sequences, and alerting businesses to responsive prospects. Think of ReachInbox as your AI-powered growth team, generating top-tier leads continuously.</p>
        
        
        
<p>One of the standout features of ReachInbox is its ability to manage large-scale cold email marketing campaigns. The platform provides everything needed to launch successful cold email campaigns, from customizable templates and A/B testing to real-time analytics and performance tracking.</p>


<p><strong>Hot Tip:</strong> Use the 7-day free trial to fully experience and understand ReachInbox.ai before starting your assignment.</p>

<h2>Overview</h2>
        <p>Our task is to use the designs and APIs provided to create a functional web app. Below are the instructions to complete the assignment:</p>
        <ol>
            <li><strong>Implement the login page:</strong> Use the design provided.</li>
            <li><strong>Onebox Screen:</strong> Once logged in, the user should be taken to the onebox screen. <a href="/google-login">/google-login</a></li>
            <li><strong>Data Fetching in Onebox:</strong>
                <ul>
                    <li><code>GET /onebox/list</code> - Fetch the list of threads.</li>
                    <li><code>GET /onebox/:thread_id</code> - Fetch details of a specific thread.</li>
                    <li><code>DELETE /onebox/:thread_id</code> - Delete a specific thread.</li>
                </ul>
            </li>
            <li><strong>Keyboard Shortcuts in Onebox:</strong>
                <ul>
                    <li><code>D</code> - Deletes the current thread.</li>
                    <li><code>R</code> - Opens the Reply box.</li>
                </ul>
            </li>
            <li><strong>Custom Text Editor:</strong> Add custom buttons like “SAVE” and “Variables” in the editor.</li>
            <li><strong>Implement Reply:</strong> Clicking on send should send a reply using the endpoint <code>POST /reply/:thread_id</code>. Required fields:
                <pre>
{
    "from": "email",
    "to": "email",
    "subject": "",
    "body": "<html></html>"
}
                </pre>
            </li>
            <li><strong>Light and Dark Mode:</strong> Implement both light and dark modes in the application.</li>
        </ol>
 <h2>Design and API Files</h2>
        <p>The design file and API documentation are available at the following links:</p>
        <ul>
            <li><a href="https://www.figma.com/file/uECxqvFhEx9dn4ZuO7wqmu/Reachinbox-Assignment?type=design&node-id=0-1&mode=design" target="_blank">Design File</a></li>
            <li><a href="https://documenter.getpostman.com/view/30630244/2sA2rCTMKr#433eb613-e405-4239-9e2d-f20485b31b27" target="_blank">API File</a></li>
        </ul>

 

<p>To run this project on your local system, follow these steps:</p>
        <ol>
            <li><strong>Clone the Repository:</strong> Open your terminal and run:
                <pre>
git clone https://github.com/ichhakumari/REACHINBOX/tree/main/OneBox
                </pre>
            </li>
            <li><strong>Navigate to the Project Directory:</strong> Change to the project directory:
                <pre>
cd REACHINBOX/OneBox
                </pre>
            </li>
            <li><strong>Install Dependencies:</strong> Run the following command to install the required dependencies:
                <pre>
npm install
                </pre>
            </li>
            <li><strong>Run the Application:</strong> Start the application using:
                <pre>
npm start
                </pre>
            </li>
        </ol>
    </div>
    <hr>
    <h2>It was a Frontend Developer assignment  provided by ReachInbox to assess participants' skills and abilities for the position.</h2>
    <hr>
</body>
</html>
