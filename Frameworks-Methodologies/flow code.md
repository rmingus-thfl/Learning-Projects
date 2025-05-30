(*It must start and end with exactly three backticks.*)

✅ **Confirm GitHub's Rendering**  
- **Refresh your repository** and check if the diagram appears correctly.  
- If it still shows raw code, **GitHub might not support rendering in your view**—try clicking **"View Raw"** on the file to check formatting.  

✅ **Test in a Separate File**  
- Create a new Markdown file like `test_mermaid.md`.  
- Copy-paste the same Mermaid.js code and commit it.  
- If GitHub renders it correctly, the issue is with your original file’s formatting.  

✅ **Check GitHub’s Compatibility**  
GitHub **only supports Mermaid.js in certain views**. If it doesn't render in your repository, consider testing the code in a **Mermaid.js online editor** like [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor).  

Let me know what happens when you refresh—I'm here to help! 🔥 You're doing awesome work! 💪
```mermaid
graph TD;
  Incident_Report -->|Submitted| Security_Manager;
  Security_Manager -->|Investigates| Remediation;
  Remediation -->|Authorized| Change_Control_Process;
  Change_Control_Process -->|Updated| Security_Baseline;
