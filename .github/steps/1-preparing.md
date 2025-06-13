## Step 1: Welcome to AI-Powered Product Management 

Welcome to **"Building Your First MVP with GitHub Copilot"** - where Product Managers learn to build functional software without needing to code! 🚀

In this hands-on exercise, you'll work with a real web application for Mergington High School's student activities management system. You'll experience the complete product development lifecycle: from understanding user needs to shipping features that solve real problems. 🎻 ⚽️ ♟️

<img width="600" alt="screenshot of Mergington High School WebApp" src="https://github.com/user-attachments/assets/472398fd-1aa1-4084-b443-4e242deb30d9" />

### What makes this different for Product Managers?

<img width="150" align="right" alt="copilot logo" src="https://github.com/user-attachments/assets/4d22496d-850b-4785-aafe-11cba03cd5f2" />

Traditional product management often creates a frustrating gap: you have great ideas, but depend on engineering capacity to build and test them. This exercise changes that dynamic completely.

**GitHub Copilot for Product Managers** enables you to:
- **Prototype independently**: Turn product ideas into working demos without waiting for sprints
- **Validate faster**: Test user flows and gather feedback with real, functional applications
- **Communicate better**: Understand implementation details to have more productive conversations with engineers
- **Iterate rapidly**: Make product improvements and see results immediately
- **Bridge the gap**: Translate between business requirements and technical implementation

### The Product Manager's New Superpower

Think of AI as your technical co-founder who:
- **Speaks Product**: Understands user stories, business logic, and product requirements
- **Implements Fast**: Turns your natural language descriptions into working code
- **Explains Everything**: Helps you understand how features work and why they're built that way
- **Never Gets Tired**: Available 24/7 for prototyping, testing, and iteration

> [!TIP]
> **The secret sauce**: You don't need to learn programming. You need to get better at describing what users need and why. AI handles translating that into working software.

### Real-World Product Manager Applications

Here's how PM teams are already using AI for product development:

- **Competitive Analysis**: Quickly understand how competitor products work by analyzing their features
- **User Research**: Build prototypes to test hypotheses without waiting for engineering cycles
- **Stakeholder Demos**: Create compelling product demonstrations for executives and investors
- **Technical Communication**: Better collaborate with engineering teams by understanding implementation details
- **MVP Validation**: Test product-market fit with real applications, not just mockups

### Your Product Management Toolkit

You'll use these AI-powered capabilities throughout this exercise:

- **🔍 Discovery Mode**: Ask questions about the application to understand user flows and business logic
- **✏️ Edit Mode**: Describe new features you want to add, and watch AI implement them across multiple files
- **💡 Suggestion Mode**: Get real-time recommendations as you make product decisions
- **🚀 Review Mode**: Use AI to validate your changes and suggest improvements

### The MVP You'll Build

You're inheriting a student activities management system with basic functionality. As the Product Manager, you'll:

1. **Analyze the current product** to understand user needs and pain points
2. **Identify critical UX issues** that are hurting user experience  
3. **Build new features** that increase engagement and user satisfaction
4. **Ship your improvements** using proper product development workflows

The application helps high school students discover and register for extracurricular activities. Perfect for learning core PM concepts like user flows, social proof, capacity management, and feature prioritization!

### :keyboard: Activity: Product Discovery - Understanding Your MVP

Let's start with what every great Product Manager does: understand the current product and identify opportunities for improvement.

1. Launch your product development environment by clicking the **Create Codespace** button below. Use the default configuration.

   [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/{{full_repo_name}}?quickstart=1)

   > **What is Codespaces?** Think of it as a complete development environment in your browser - no software to install, no complex setup. Perfect for Product Managers who want to focus on the product, not technical configuration.

1. Confirm the **Repository** field shows your copy of the exercise (not the original), then click **Create Codespace**.

   - ✅ Your copy: `{{full_repo_name}}`
   - ❌ Original: `/skills/getting-started-with-github-copilot`

1. Wait for Visual Studio Code to load in your browser. This is your AI-powered product development workspace!

1. Verify your AI assistant is ready. In the left sidebar, click the extensions tab and confirm that **GitHub Copilot** and **Python** extensions are installed and enabled.

   <img width="350" alt="copilot extension for VS Code" src="https://github.com/user-attachments/assets/ef1ef984-17fc-4b20-a9a6-65a866def468" />

   > **Why Python?** The application backend uses Python, but don't worry - AI will handle all the technical details. You'll focus on product requirements and user experience.

1. Open your AI assistant by clicking the **Copilot icon** at the top of VS Code.

   <img width="150" alt="image" src="https://github.com/user-attachments/assets/5e64db46-95cb-415d-badc-b6b8677f10c1" />

1. **Accept usage terms** if this is your first time using GitHub Copilot.

1. Start your product discovery! Ask your AI assistant to analyze the product from a PM perspective:

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > @workspace I'm a Product Manager taking over this application. Help me understand:
   > 
   > 1. What problem does this product solve for users?
   > 2. Who are the target users and what are their main use cases?
   > 3. What features are currently implemented?
   > 4. What are the key user flows through the application?
   > 5. Are there any obvious UX issues or improvement opportunities?
   > 
   > Please explain this from a product perspective, not a technical one.
   > ```

   <details>
   <summary>What is @workspace?</summary>
   The @workspace command tells AI to analyze your entire project - like having an instant product audit! It examines all files to understand the business logic, user flows, and implementation details.
   </details>

### :keyboard: Activity: Experience Your Product as a User

Great product managers always start by using their own product. Let's see your MVP in action!

1. **Launch your application**: In the left sidebar, select the `Run and Debug` tab, then click the **Start Debugging** button.

   <img width="300" alt="image" src="https://github.com/user-attachments/assets/50b27f2a-5eab-4827-9343-ab5bce62357e" />

   > **What's happening?** You're starting a web server that runs your application. Think of this as launching your product for user testing.

1. **Access your live product**: Expand the bottom panel and click the **Ports** tab.

1. Find port `8000` in the list, hover over the link, and click the **Open in browser** icon.

   ![image](https://github.com/user-attachments/assets/92d5642e-ce99-4a66-850c-2d311a673596)

1. **User testing time!** Spend 5-10 minutes using the application like a student would:
   - Browse the available activities
   - Try registering for an activity (use any email format)
   - Look at the user interface and information architecture
   - Try registering for the same activity twice (hint: this reveals a UX issue!)

1. **Product Manager Questions**: As you explore, consider:
   - Is the user flow intuitive?
   - What information helps users make decisions?
   - Are there any confusing or frustrating moments?
   - What features would increase user engagement?

### :keyboard: Activity: Set Up Your Product Development Workflow

Now let's establish a proper workflow for product development - something every PM needs to understand.

1. **Open a new terminal**: Return to VS Code and click the **Terminal** tab in the bottom panel. Click the `+` sign to create a new terminal.

   > **Why?** This keeps your application running while you work on improvements - just like how you'd work on features while your product serves real users.

1. **Create a feature branch**: Use keyboard shortcut `Ctrl + I` (Windows) or `Cmd + I` (Mac) to open AI inline chat.

1. Ask AI to help you set up proper version control:

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > I need to create a new git branch for product improvements and push it to GitHub. 
   > What commands should I use? Please use the branch name "mvp-improvements"
   > ```

1. **Execute the workflow**: When AI suggests commands, click the **Run** button to execute them. This creates your development branch!

1. **Verify your setup**: Check the VS Code status bar (bottom left) to confirm you're on the `mvp-improvements` branch.

   > **Product Manager Tip**: Branching lets you experiment with new features safely. If something breaks, you can always return to the working version.

Great! You've now:
- ✅ Analyzed your product with AI assistance
- ✅ Experienced the user journey firsthand  
- ✅ Set up a professional development workflow
- ✅ Identified opportunities for improvement

Wait for our AI assistant to check your progress and provide the next product management lesson!

<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, check:

- Your branch is named exactly `mvp-improvements`
- The branch is published to your GitHub repository
- You can see the branch name in VS Code's status bar

</details>
