# Using SSH
You can use HTTPS or SSH to connect or communicate your machine to GitHub. 

The problem with HTTPS is that you will be prompted muliple times to enter your GitHub credentials when working with GitHub. You can avoid this by using SSH. 

GitHub Docs covers Connecting to GitHub using SSH [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh).

Once the key has been generated and added to your GitHub account, you can test Back on your machine, you can test SSH by typing in a cmd.exe: 

`ssh -T git@github.com`

You should see a message that you've successfully authenticated with GitHub. 