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
  1° ToolBar. Permits to :
    1.1° Open Existing Workflow from Disk (File browser).
    1.2° Save Workflow to Disk
  2° Left/High Panel. Permits to create Resources (an Icon per resources): 
    2.1 SMTP Server Connection.
    2.2 Web Driver Connection.
    Rq : list will evoluate during the project 
  3° Left/Low Panel that contains workflow policies :
    3.1° Mail events (Send/get/..)
    3.2° Web Scrapping (Click/Fill Form/Check Field value/..)
    3.3° Variable management (Create Variable/Set value/ Get Value/ compare value to regex/..)
  4° Right Panel: Main designer
    4.1° Initially, This pannel contains : A Start (empty activity) and a (Stop empty activity).
    4.2° Then, all activity should be added by Drag and drop from Pannel N°3.
    4.3° When double clicking on an activity you have a form with the activity defintion.
 
 ## Delay
 
Interface delivery is excpected for Q2 2019 (End of June 2019).
