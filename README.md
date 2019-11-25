# CodePilot  - Advanced code search tool
 Key capabilities
 Profiles
 Local repository
 Mutiple Sources
 Setup profile

Before I do a code search lets go to the profile settings and explore various developer profiles. Profiles basically gives you ability to customize codepilot based on the developer skills. We can choose from existing list or we can modify existing profiles or we can create a new profile of our own. Here you can set programming languages, IDE where you will be primarly developing, frameworks/libraries, databases etc. The result set will be filtered based on the profile we select.
### Use cases
As a java developer i always have trouble using the java 8 stream API. I do not remember on top of my mind how to implement it.  So I want to learn Java Stream API
## Viewpoint

Codepilot is an opensource tool that can be customized according to company standards. It has the capability to create various developer profiles, add multiple sources, extend programming language support and customize the search settings.

It has the richness of smart code assist features that enterprise can leverage by forking the GitHub codebase and extending it. We strongly recommend to extend REST API developed by us as part of this PoC , customize codepilot profiles, connectivity with multiple repositories, effective usage of the code repository search results for developers, understand and extend the core brain of codepilot to data science machine learning use cases where data scientist and machine learning engineer need contextual metadata about a data set during their ML development, leverage frequently updated programming languages version like JAVA 12+/Python 3.6+/Cloud APIs/DevOpscodesnippet and so on

# DeepCode.AI – Code recommendations tool
## Key capabilities
Dynamic code recommendation
Code analysis through commit and pull requests
Plugin support.
Public REST API functionality 
## Registration with code repository
Navigate to www.deepcode.ai and click analyze your code now button. It prompts you to login via github, bitbucket, gitlab.com. I choose github for this demo. Click on github it redirects you to github login screen where you enter your organization credentials then redirects back to deepcode dashboard screen.  
You can see I have one private repository which consists of a java app. Go ahead click on audit button. Here it uses artificaial intelligence to analyze the files under this project and Here you can see metrics in left most panel, suggestions which divided into critical, warning, info catagories in the middle panel, We can view more information about the suggestions in the right most panel.

## Use cases
## VSCode extension
Show Installed version on visual code
## Viewpoint

DeepCode already has IDE based smart code assistants. We collaborated extensively with DeepCode team and support from them was positive. They could share how we can use that tool, what use cases we should focus on and responded to email communications. This indicates they are confident on their product capabilities and open to make their product enterprise ready.

While developing the use cases for this project, we felt this could be en extended engineering capability in an enterprise DEV-Ops life cycle because of its code analysis against multiple repositories instead of static code analysis. We recommend to partner with DeepCode team in obtaining the on premise installation and we can supporting integration of DeepCode across various applications. The machine learning oriented code analysis capabilities has a great potential to understand and extend th for identifying the vulnerabilities that specific to an enterprise need. VS code plugin is another area we recommend embrace in every application development to improve the consistency of API usage, home grown middle ware/UI frameworks usage through DeepCode plugin smart code assistant.

# Codota AI– Commercial enterprise code search tool 
Codota's AI learns from existing Java code to assist developers to build code faster, simpler and smarter. Codota uses already learned code models to recommend relevant code. These quality of the suggestions are amazing. It makes the developer's programming experience significantly faster and better. It combines techniques from program analysis, natural language processing, and machine learning to learn from code

Codota's AI auto-complete is going to be triggered whenever the tool discovers useful suggestions to provide. Like suggestions pop up while assigning values to the variables example: once typewriting “var x = "). Codota is constantly learning the code models and helps the suggestions to be quicker and better (such as within loops and conditional statements).
Codota is still growing, for example, the usage of annotations, decorators are not that good.
Currently, Codota supports Java, Kotlin and Javascript programming languages. It supports the IDEs like Intellij Android Studio Eclipse Luna (4.4) or newer.

# Icode 
Hi everyone, in the last few mins we have seen various tools like codepilot, deepcode, codata. Just like anyother emarging technology tool, No tool gives you end to end solution for example codepilot provides certain capabilities , deepcode provides certain capabilities, codata focus on java, javascript but not beyond databases. it made us to think, you know what we need to have a unified solution which will integrate with these three tools, not only with these three tools, in future other tools, it could be test magic, it could be Tableau AskData or various tool. So we thought that this could be a wrapper tool that integrates and provides contextual help, that tool we are calling it as a unified intelligent tool also called as icode. 

Here comes the icode implementation, thought process, and everything. iCode is a software application thou we built it as a web application but we designed or envisioned to be a plugin to an IDE. its primary capability is to understand the contextual code, provide a configuration capability where a developer can say they want java, python or database/ unit testing and provide recommendations contextually based upon the developer configurations. 

Icode also known as intelligent code where call a server component which could be codepilot executed few mins back or we can integrate API with DeepCode or we can integrate API with test magic. We can consolidate all those results from various intelligent code analysis, apply some intelligence on the consolidated data, that could be removing the duplicates or templating the data based on the enterprise needs specific to business unit or specific to technology stack and give a smart intelligent code.
