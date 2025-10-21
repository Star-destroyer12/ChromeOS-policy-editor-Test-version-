IN ORDER TO DO THIS ON A MANAGED CHROMEBOOK, YOU MUST FIRST USE SH1MMER. 

NOTE:

You must be in developer mode with RootFS verification disabled. Must be on ChromeOS version 116 or earlier unless you are willing to make the image yourself.

NOTE 2:

I do not reccomend using this as it is incomplete, and could possibly get you in trouble or break your chromebook. I am not responsible for any damages, you bring any and all repercussions on yourself the second you begin the procress.

Step 1:

download and edit the newpolicy.json file to your liking, then upload it to github in a manner similar to this.

step 2:

Open crosh, 

shell, 

sudo -i, 

cd .. , 

cd /etc/opt/chrome/policies/managed, 

Ls, 

cd managed (or whatever it says), 

Ls, 

curl -O https://raw.githubusercontent.com/Star-destroyer12/ChromeOS-policy-editor-Test-version-/refs/heads/main/newpolicy.json

cat newpolicy.json > policy.json

After this, you should be done. Reload your policies, and check the policies you changed if this did not work, please tell me I will try to help. 

I will make a way to easily edit your policies some day soon but am currently testing if I can actually do that. 
