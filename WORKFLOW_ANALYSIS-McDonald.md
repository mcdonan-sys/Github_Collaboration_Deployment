WORKFLOW ANALYSIS  
What triggers this workflow to run? The “on:” section includes “push” to the “main” branch.  
What are the four main steps this workflow performs? Checkout code, Validate HTML, Check for broken links, and Deploy to GitHub Pages.  
What does the "Checkout code" step do and why is it necessary? It creates the repository content into the runner, making code available for the next steps.  
What is the purpose of the environment configuration? Ensures secrets and settings are used securely and consistently.  
How does this automated deployment improve reliability compared to manual deployment? Automated checks reduce manual errors, ensure code is tested before deployment, and speed up the workflow.  
What would happen if you pushed code to a different branch (not main)? The workflow wouldn’t trigger since it's only set to run on pushes to “main”.

