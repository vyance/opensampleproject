# opensampleproject
<h1>Backend for IOS application and webview. For mostly read purposes.</h1>
<div/>
<div>Allows use to sign up with IOS device, and verify their number using sms.</div>
<div/>
<div>User then can add other users as contacts with sms or email messaging capabilites.  If the contact already has an account or creates an account, the application switches to in-app messaging.</div>
<div/>
<div>Installation</div>
<ul>
<li>'npm install' to download packages.</li>
<li>'node index.js' will run server</li>
<li>You will need twilio and postmark api keys in the enviromental variables to fully run code.</li>
<li>Apn notifciations are currently disabled in open code.</li>
<li>Code is designed to deploy on heroku with mongodb.</li>
</ul>
<div/>
<div/>
<div>Testing</div>
<ul>
<li>'npm test' will run tests</li>
</ul>

<div/>
<div>Notable files</div>
<div>app/routes.js</div>
<ul>
<li>contains routes to relevant controllers</li>
</ul>
<div/>
<div>test/routesTest.js</div>
<ul>
<li>contains end to end intergration testing</li>
</ul>

