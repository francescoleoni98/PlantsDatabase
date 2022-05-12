# PlantsDatabase
PlantsDatabase is a growing collection of plants and flowers.

It aims to collect reliable indications about plant care, problems and history, and made them available through an easy-to-use website.

## Model
The complete list of information for each plant is the following (this list may expand in the future) along with images.

- name
- classification
- description
- size
- temperature
   - summer_min
   - summer_max
   - winter_min
   - winter_max
- location
   - description
   - inside_min_month
   - inside_max_month
   - outside_min_month
   - outside_max_month
- cycle
   - vegetation_min_month
   - vegetation_max_month
   - dormancy_min_month
   - dormancy_max_month
- blooming
- watering
- nebulization
- repot
   - description
   - min_month
   - max_month
- soil
- fertilization
- pruning
- moltiplicazione
- toxicity
- parasites
- illnesses
- species
   - name
   - image
   - description


# **Guidelines**
If you want to contribute to PlantsDatabase and make it better, your help is always appreciated.

## **To make a good pull request**
1. Fork the repository to your personal Github. Forking is basically an easy way to make a duplicate of the repository to your own account.
2. Now that you have forked the repository to your account, go to the repository in your account, then click on the clone button and hit the copy to clipboard icon.
3. Now, open a terminal on your local machine and clone the forked repository by doing: `git clone <copied url>`. For example: `git clone https://github.com/<your-github-username>/PlantsDatabase.git`
4. Create a branch in git inside your local machine: `git checkout -b <branch-name>`
5. Now you can fix bugs or do whatever you need to do in order to improve the code in the project. Follow the code style of the project, including indentation. If the project has tests run them! Write or adapt tests as needed. Add or change the documentation as needed. Remember to make sure the changes are applied only to the branch you created!
6. Open `CONTRIBUTORS.md` in a text editor and add your name to it. Don’t add it at the beginning or the end of the file, add it anywhere in the middle of it. Now, save the file.
7. Commit those changes by doing `git commit -m "Added <your-name> to contributors list`
8. Push those changes to the forked repository on Github via: `git push origin <your-branch-name>` replacing “<your-branch-name> with the name of the branch you created earlier.

## **Submit your changes for review**
If you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button.Now, submit the pull request.

Congrats! You have successfully contributed to PlantsDatabase repository. 

Now you’ll just have to wait for the repository owner/admins to accept your pull request.
