NOTE:

You must be in developer mode with RootFS verification disabled. Muct be on ChromeOS version 116 or earlier unless you are willing to make the image yourself.

Step 1:

download and edit the policy.json file to your liking, then upload it to github in a manner similar to this.

step 2:

Open crosh, 
shell, 
root, 
cd .. , 
cd /etc/opt/chrome/policies/, 
Ls, 
cd managed (or whatever it says), 
Ls, 
curl -o https://raw.githubusercontent.com/StarkMist111960/ChromeOS-policy-editor-Test-version-/refs/heads/main/newpolicy.json (Or your github raw user content),
cat newpolicy.json > policy.json

After this, you should be done. Reload your policies, and check the policies you changed if this did not work, please tell me I will try to help. 
