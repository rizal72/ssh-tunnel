# ssh-tunnel
tunnel port 22 from serveo.net for remote access:  
uses autossh, ssh -R option and serveo.net online service.  
Usage: ssh-tunnel -s/-g [-b]. 
  
**Modes:**  
-s    	[s]tandard port 22 SSH tunnel, with alias: rizal72.  
-g		[g]eneric TCP tunnel, use port 1972.  
  
**Available options:**  
-a=ALIAS	set a custom [a]lias.  
-f		execute in background.  
-h		prints this help.  
