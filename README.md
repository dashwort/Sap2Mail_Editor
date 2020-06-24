# Sap2Mail_Editor
Repository used for distribution of public NuGet Packages

## Purpose: 
This tool aims the simplify the creation of HTML based templates for the Sap2Mail application and lower the barrier to entry for users. The tool is based on C# and uses the MSHTML engine to automatically generate the template html.  

### Why have an installer?
Besides quickly updating to the latest release, this allows us to have a consistent rollout strategy and further lower the barrier to entry. The installer places the application under the user’s appdata folder. This means that no administrator rights or prompts are required to install the latest version of the tool and allows the update task to complete automatically in the background. 

### Items to note
1. Help items are for internal use only and documents will not load unless on corporate network.
2. Template Sync is not externally configurable, must be on corporate network to work.
