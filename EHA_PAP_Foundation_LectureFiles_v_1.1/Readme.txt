///////////////////////////////////////////////////////////////////////////
E-Houdini Academy - Procedural Production Masterclass - Foundation Module

EXAMPLE FILES V_1.1
Houdini 18.5 & 19 compatible
Last tested on Houdini 19.0.490
///////////////////////////////////////////////////////////////////////////


	Welcome and thank you for downloading the E-Houdini Academy
	Free Introduction Assignment for the "Procedural Asset Production" Masterclass.

	My name is Erwin Heyms and I have been a professional procedural artist and Houdini teacher for nearly a decade.
	I have worked on several tripple A video games, including UBISOFT's Ghost Recon Wildlands and Breakpoint.

	In 2020 I decided I wanted to create a full masterclass for public release and have been working hard on this course since.
	And I've been able to do this thanks to the support I receive from my patreon backers at www.patreon.com/erwinheyms
	And it is thanks to the support of my patrons that I am releasing the Introduction module of the masterclass for FREE with Houdini HIVE 2021.


////////////////////////////////////////////////////////////////
ABOUT THE MASTERCLASS:
////////////////////////////////////////////////////////////////

	The HOUDINI "Procedural Asset Production" Masterclass

	This masterclass is a Comprehensive Multi-stage Course on Professional Digital Asset Development for Game-dev Pipelines, 
	featuring the Unreal engine.

	Its aim is to bring a Houdini user at any skill level up to a high professional level for creating tools aimed at World Builders, 
	Level Designers and Archviz Artists. 

	By following the masterclass you will gain:

	- A thourough understanding of Houdini's node language. 
	- Hone your skills at Procedural tool and Procedural pipeline design.
	- Thoroughly understand VEX & Python Script for Houdini
	- Learn how to create clear and easy to use tool User interfaces. 
	- And set up a powerful data management pipeline for your toolsets.

	It is slated to be released in stages over the course of the second half of 2021 and 2022.


	For more information about the masterclass: 

	Visit the Masterclass project page at: 					https://ehoudiniacademy.com
	For more information about my patreon program, see the FAQ at: 		https://patreon.com/erwinheyms
	Or join my public Discord channel at:					https://discord.gg/BKtNSs7kpE
	

/////////////////////////////////////////////////////////////////
GETTING STARTED:
/////////////////////////////////////////////////////////////////

	To get started with this project there are several folders.

	In the main folder you will find the scene file for this lecture.
	The "HDA" folder contains the example assets .HDALC
	The "geo" and "tex" folders contain the .FBX models and textures needed for this module.

	Further information about the course and its structure, please see the masterclass page at https://ehoudiniacademy.com



	/// To view the example project in Houdini, follow the Lecture videos or follow this guide:
	
	- It is recommended that Houdini 18.5.596 or higher is installed on your system.
	- Houdini 19.0.490 or higher is supported as well.
	
	- Open Houdini.
	- Press "File / Set Project". And set the "Foundation_Assignment" folder as the current project.

	- Make sure the HDA are installed to the current HIP file by pressing "File / Import / Houdini Digital Asset".
	  From the Install Digital Asset Library window, click the browse button next to the top bar and browse for the hda folder in the project folder.
	  Select and load all ".hdalc" files. These will appear in the dialoge below. Press Install.

	- Open the ExampleScene.hiplc file from the project folder.




	/// To view the example project in Unreal, follow the Lecture videos or follow this guide:

	- place the UnrealProjectFiles folder in a file location with less than 300 characters (or Unreal will be unable to save the generated files.)	
	- Open the foundation_Example.uproject with the unreal engine (version 4.26.2 or higher).
	

	/// To run the Project Tool in the Houdini Engine in Unreal

	- Go to the HoudiniEngine/PluginSettings menu and find the "Otl Search Path".
	- Specify the full file path for the HDA folder ( ../UnrealProjectFiles/Content/HDA )
	  This will make sure the Houdini Engine can find all the HDA components for the example tool.

	- Restart Unreal, Load the "Foundation_Example.uproject"
	- Go to HoudiniEngine/CreateSession (this will start the Houdini Engine).

	- You should now be able to edit the building tool.


	///Troubleshooting:

	  If the Houdini Engine Session does not start, check if your Houdini License Administrator is running and the Houdini Engine Indie (or commercial) License is installed.
 	  Though it is possible to get a free houdini Indie license from the sidefx.com website and install that alongside a Houdini Commercial license.

	  Check if you are running a Houdini Engine Commercial license instead of a Houdini Engine Indie License ( It is not possible to cook the Houdini Indie .HDALC example files with a commercial license ).

	  If you are running a Commercial license, and are unable to use the Indie example files, see the Houdini "hda/18.5_CORE" folder for commercial .hda versions of the toolset.

	  If the tool cooks correctly, but unreal does not allow you to save the resulting mesh(es) , check if the file path of the UnrealProjectFiles folder path is too long.



	


/////////////////////////////////////////////////////////////////
LECTURE CONTENTS:
/////////////////////////////////////////////////////////////////

	This "Intro Assignment" is seperated into 2 parts.

	- 1. The introduction to Houdini.

	Part 1 will teach complete beginners to Houdini how to understand its interface, data structure, node language and terminology.
	We will also have an overview of the Houdini Engine in the Unreal Engine 4.


	- 2. The Intro Assignment project.

	Part 2 will see us construct a simple but versatile building, using Houdini's node language.

	In this we will construct a building with variable floors, windows and doors.
	We will then add decoration elements such as pillars and elevator and staircase shapes to the building.
	We will set up this structure so it can be used and viewed in the Unreal Engine 4 (assuming you have Houdini Indie).
	Next, we will add a more detailed balcony to the building, and improve the elevator and staircase shapes so they can be traversed by the player.
	We will create a texturing asset and apply textures to the building.
	And Finally, we will perform an optimization pass to make the asset cook significantly faster.





