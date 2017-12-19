This is just a Reflecting pool of idea paddings for this project 
   (*this is more a Note2Self* so these aren't just forgotton)

## Ideas,Suggestions,impossiblities made possible, or the not even possible but what if's .
-- CI-CD intregtions
- build our own docker image(s) (image-chain) for our CI-tests, maybe multi-Os, and codestyle/GC/and debugging.
.
-- Maybe not doible but planting the seed... **this has been an idea brewing since pulling MySQL.** 
- think about using MangOS inspired method for making ACE Wrappers external Lib  (xamp: light's hope)
    
	~~the whole thought process behind this idear.
	Biggest reasoning is cuz updating this (intern)--slim lib... is painfully time consumming, and now we're so far behind on revisions, 
	that a normal cut-n-paste update is no longer optional, a full over-haul of lib will be needed.  

    Pro's of the change:
      (1) Lightens weight of repository, making it better for pull/clone/fetch times.	
      (2) speeds up build-time because it is externally built.
	  (3) Opens up extensionablity for our core project. 
          (A.)  Extension Lib Option 1, can Add Developer Option for "FrameWork Type" ACE/Boost/pThreads/POCO/AIO etc).
		          -there are other (OO)frameworks for networking and/or inter-process communication w/-MT out there.
		  (B.)  Extension Lib Option 2,  can Add Developer Option for "Database Type"" SQLite/PostGre/MySQL/MsSQL etc).		
		          -three of these were once already in the legacy core...
				  
      (4) extensions always bring in more ppl( we know what that means), 
	            More Options and better choices then what the other emu service communities have (that are still worth mentioning).
    
	Con's of the change:
      (1) the Comm. Help section Of forums will be Filled with wtfs/how2's/and troll food. need knowledgible ppl moderate and help.
	  (2) new docs/wiki will have to be made for eternal package build/install of these extensions for the core build types.
      (2) The amount of code in our source that needs converted to accept/connect/utilize all the Extension type Options@ build-time, 
	        - not sure our curr. core model will simply(if it can at all) Be adaptible 2 accept a major swapping Library function like would b.
			
      (3) core libs will have to be designed for --slim (Lite versions) Lib distros, that is; if we want our own "Official" lib packages for project. 
	        - This is something that would need to be done-2 cut-down on possible compatiblity/stupidity issues that would surely arise.
			
	  (4) Would need alot more member activity, more advanced dev personal, to cover the developments of the "Official Libs" 
	        - as well as core engineers to work on the core it self. this would be great for a large team project, lol.
			
	