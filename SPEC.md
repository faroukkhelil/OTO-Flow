## Problem
At v1.0 OTO-Mate is yet an RPA solution (Robotic Process Automation).

Its able to do multiple tasks :
  - Web scrapping
  - File R/W operations
  - and a lot of other tasks ...

Today OTO-Mate is configurable through JSON file sets.

To reduce design cost & lower time to Market, We are wiling to create a web interface that permits :
  - The design of an automation Workflow using drag&Drop.
  - Generates OTO'Mate JSON files.

## Main prupose
OTO-Flow will be the designer UI of OTO-Mate.
The expected delivery is a Web interface that permits to :
  - Design a full Workflow using drag and drop button.
  - Open existing Workflow JSON files
  - Save Workflow as Json File
  
JSON file Syntaxe will be provided later.


## Specification
The web UI is composed of 4 panels :
  - ToolBar. Permits to :
    - Open Existing Workflow from Disk (File browser).
    - Save Workflow to Disk
  - Left/High Panel. Permits to create Resources (an Icon per resources): 
    - SMTP Server Connection.
    - Web Driver Connection.
    Rq : list will evoluate during the project 
  - Left/Low Panel that contains workflow policies :
    - Mail events (Send/get/..)
    - Web Scrapping (Click/Fill Form/Check Field value/..)
    - Variable management (Create Variable/Set value/ Get Value/ compare value to regex/..)
  - Right Panel: Main designer
    - Initially, This pannel contains : A Start (empty activity) and a (Stop empty activity).
    - Then, all activity should be added by Drag and drop from Pannel N°3.
    - When double clicking on an activity you have a form with the activity defintion.
 
 ## Delay
 
Interface delivery is excpected for Q2 2019 (End of June 2019).
