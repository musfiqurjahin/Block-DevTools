<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Block Developer Tools - Created by JaHIN</title>
</head>
<body>
    <h1>Block Developer Tools</h1>
    <p>This code disables common methods to access developer tools on a webpage.</p>

 <h2>Features</h2>
    <ul>
        <li><strong>Disable Right-click:</strong> Blocks the context menu when the user right-clicks anywhere on the page.</li>
        <li><strong>Block F12:</strong> Prevents the user from opening developer tools using the F12 key.</li>
        <li><strong>Block Ctrl+Shift+I / Ctrl+Shift+J:</strong> Stops the user from opening developer tools or the console via these keyboard shortcuts.</li>
        <li><strong>Block Ctrl+U:</strong> Prevents the user from viewing the page source with Ctrl+U.</li>
        <li><strong>Redirect:</strong> When any blocked action is detected, the user will be redirected to a specified URL.</li>
        <li><strong>Alert Notifications:</strong> Alerts notify the user that these actions are disabled.</li>
    </ul>

 <h2>How to Use</h2>
    <ol>
        <li>Copy the JavaScript code provided.</li>
        <li>Paste it into your HTML file within a <code>&lt;script&gt;</code> tag.</li>
        <li>Customize the URL in the code to set where users should be redirected when trying to access developer tools.</li>
        <li>The script will run automatically once added to your page, blocking the listed actions.</li>
    </ol>

 <h2>Important Notes</h2>
    <ul>
        <li>This script is intended to discourage casual users from accessing developer tools but is not a foolproof security solution.</li>
        <li>Experienced users can still bypass these protections. It's always important to secure your data on the server-side.</li>
    </ul>
</body>
</html>
