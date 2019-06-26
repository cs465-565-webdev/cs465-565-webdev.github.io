### Setting up your environment

#### Cloning an existing Git repo

Via your CLI, navigate to your preferred directory: `cd /path/to/your/repos/directory`

Clone the `teaching-webdev` repository

- `git clone https://github.com/sniklaus/teaching-webdev` to create a `teaching-webdev` folder 

- `git clone https://github.com/sniklaus/teaching-webdev <folder-name>` to create a folder called <folder-name>

#### Create a GitHub or BitBucket repo

- Create a private repo

- Search for Caterina Paun to add as a collaborator

- Copy the link to this repo, which is your `<remote_repo_url>`

#### Configuring your repo for remote collaboration

- Check your remotes: `git remote –v`

- If you already have an origin (pointing to Simon’s repo), you will need to rename or delete it

To delete a remote, use `git remote rm origin`

- Add the URL of your GitHub repo as the origin: 

#### Do not push your credential to GitHub

- Create a `.gitignore` file and add your credentials file: `echo 'setup.bash > .gitignore`

#### Push your local files to the remote

- `git remote add origin <remote_repo_url>`
