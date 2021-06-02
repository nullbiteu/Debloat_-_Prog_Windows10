# Debloat_-_Prog_Windows10
"Bereinigung" eine Windows 10 Installation + Installation von Programmen über den Paketmanager Chocolatey

Installiert automatisiert nützlich Programme über den Paketmanager Chocolatey

7Zip      
Attributechanger             
Hwinfo			                  
Rufus				     
Putty			       
Treesizefree	                                              
Runasdate			                 
Mpc-be			    
Irfanview			   
Anydesk			    
Skype				      
Eraser			       
Bleachbit                                                                                                                             	                                                                                                                    	 
Autolt                                                                                                                                
WinSCP		                      
Python			    
Notepad++   	  

**Aktivierung der Ausführung des PowerShell-Skriptes**

**Bei folgender Fehlermeldung:**

"Die Datei "C:\Users\....._Windows10.ps1" kann nicht geladen werden. Die Datei "C:\Users\....._Windows10.ps1" ist nicht digital signiert. Sie können dieses Skript im aktuellen System nicht ausführen. Weitere Informationen zum Ausführen von Skripts und Festlegen der Ausführungsrichtlinie erhalten Sie unter "about_Execution_Policies".."

PS> 
 Set-ExecutionPolicy Unrestricted -Scope CurrentUser 
 
 Set-ExecutionPolicy Allsigned -Scope CurrentUser 
 
 Set-ExecutionPolicy Restricted -Scope CurrentUser 

**Entsperren von PowerShell-Skripten und -Modulen in diesem Verzeichnis:**

PS> 
ls -Recurse *.ps*1 | Unblock-File
