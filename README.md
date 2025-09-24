## GitHub Activity Feed Plugin Example
Github Activity feed Plug-in - Simple Snippet ( .html, .js)

===

### 🚀 How It Works
1. Load required dependencies:
   -   (*) This plugin often required the Mustache templating library and Octicons for icons.
2. Integration:
   -   Javascript (.js) and style sheets (.css) for the plugin, Mustache, and Octicons in the ```<head>
4. Add container elementent:
   -   ```
       <html>
       <head>
          <title>GitHub</title>
       </head>
      <script>
        GitHubActivity.feed({ username: "your-github-username", selector: "#github-activity-feed" });
      </script>
      ```
