## GitHub Activity Feed Plugin Example
This project shows how to integrate a **GitHub activity feed** into any HTML website using a simple JavaScript plugin.


---
### ✨ Features
   -   📡   Pulls recent activity from your GitHub profile
   -   🎨   Uses **Octicons** for pretty icons
   -   🧩   Powered by **Mustache.js** for templating
   -   💻   Simple copy-paste integration into any HTML site

### 🚀 How It Works
1. Load required dependencies:
   -   (*)   This plugin often required the Mustache templating library and Octicons for icons.

2. Javascript Snippet:
   
     ```
     <script>
             GitHubActivity.feed({
                username: "your-github-username", // 🔧 replace with username
                selector: "#github-activity-feed"
             )};
      </script>

     ```

3. Integration:
   -   Javascript (.js) and style sheets (.css) for the plugin, Mustache, and Octicons in the ```<head>
4. Add container element:
   
      ```
       <html>
          <head>
             <title>GitHub</title>
          </head>
          <body>
             <div id="github-activity-feed"></div>

             // script
   
          </body>
       </html>
      ```
