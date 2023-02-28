Git Assignment

**Step 1-** First created a directory named gitAssignment and created a readme.md file

```bash
mkdir Git_Assignment
mate Readme.md
```

**Step 2-** Then initilised that file with git file.
```bash
git init
```
        
        
**Step 3-**  Then from main branch Created two branch named Integration and Hotfix. 
```bash
git checkout -b Integration
git checkout -b Hotfix
```

        
        
**Step 4**- Then switched into Integration branch and Created two sub branch of integration branch named Feature1 and Feature2. 
```bash
git checkout Integration
git checkout -b Feature1
git checkout -b Feature2
```
      
      
**Step 5**- Commited some changes in Feature2 then pushed branches to remote and created a pull request in github and added 2 reviewer "my friend Purushotam and Sharthak" and merge this feature branch to integration Branch using github UI.  

```bash
git add Readme.md
git commit -m "Readme updated"
git push -u origin main
git push -u origin Integration
git push -u origin Hotfix
git push -u origin Feature1
git push -u origin Feature2
```bash                       
                       
**Step 6**- Made some changes in to Feature1 branch and commited it and rebase it to integration branch.  

```bash
git rebase integration
```
        
        
**Step 7**- Created Pull Request, added 2 reviewers, as Sharthak and Purushotom, and both agreed and reviewed the PR then i Merged the PR.


**Step 8**- Made some changes in Feature1 branch and then commit it , and then Created Pull Request, added 2 reviewers & merged it into Integration, Hotfix, and main branch.

**Step 9-** Commited some changes in the Hotfix branch and Created Pull Request, added 2 reviewers, got the PR reviewed & merged it into the main as well as the Integration branch.

**Done**


<img width="1121" alt="Screenshot 2023-02-28 at 6 00 32 PM" src="https://user-images.githubusercontent.com/122512155/221854762-eeab7489-5b21-4991-b10a-b06040cae27d.png">


