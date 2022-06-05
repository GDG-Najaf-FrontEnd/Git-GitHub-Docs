## Connecting to GitHub with SSH key

### Intructions

### Generating an SSH key
1. Open the Terminal/Git Bash
2. Use this command to generate a key <br />
  `ssh-keygen`
3. The command prompts you to answer some questions about the path, file name .. etc. you can just skip them by pressing enter.
4. The command generates an SSH key pair consisting of a **public key** and a **private key**, and saves them in the specified path.
5. The file name of the private key is created automatically `id_rsa`, and you never share it with anyone.
6. The file name of the public key is created automatically by appending .pub to the name of the private key file. For example `id_rsa.pub`.


### Connect to GitBub
1. Navigate to the SSH key file tha's generated: `cd ~/.ssh`.
2. Use the cat command To get the public key: ` cat ~/.ssh/id_rsa.pub`.
3. Copy the output which is the public key that starts with `ssh-rsa`.
4. Go to your GitHub => Click your avatar and choose **Settings**.
5. Select **SSH and CPG Keys**.
6. Click **new SSH key**
 <img width="400" alt="Screen Shot 2022-05-16 at 5 23 46 PM" src="https://user-images.githubusercontent.com/66907264/168615037-ba23f14a-19f6-4f7c-8ada-2764b90fa047.png">
 
 - In the title field: enter a title (it could be whatever you want).
 - In the Key field: paste our public key. 

7. Click **Add SSH key**.



And good luck with new life with your local and remoter repositories. 🥳

