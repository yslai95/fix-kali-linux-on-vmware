After install Kali Linux on Vmware Player, and you unable to update repository. (apt-get update) or install any package. (apt-get install) 

Navigate to  /etc/apt/sources.list

Open the file with text editor

Remove all content in the file

Add this "deb http://http.kali.org/kali kali-rolling main contrib non-free" 

Save & Exit

Now, RUN apt-get update
