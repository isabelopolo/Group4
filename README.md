# Group 4

1. Forming groups and assigning roles
   - Isabelo Hingpis → Repo Owner
   - Grushelika Avila → Feature Developer A
   - Aljune Baldota → Feature Developer B
   - Romulo Genoguin  → Feature Developer C
   - Luke Egarta → Reviewer / Merger
   

2. Creating and cloning the repository
   Isabelo (Repo Owner) created a repository named "group4" on GitHub 
   and added all members as collaborators. Each member cloned it into VS Code:
   git clone https://github.com/isabelopolo/group4.git
   cd group-project

3. Branching
   Example: Each developer created their own branch:
   git checkout -b feature-A   # Grushelika Avila
   git checkout -b feature-B   # Aljune Baldota
   git checkout -b feature-C   # Romulo Genoguin
   git checkout -b review-branch # Luke Egarta (Reviewer)


4. Making changes and committing
   - Grushelika Avila (feature-A) → created `about.md`
   - Aljune Baldota  (feature-B) → created `contact.md`
   - Romulo Genoguin   (feature-C) → created `services.md` 
   - Luke Egarta (review-branch) → prepared `readme.md`

5. Pushing and pull requests
   Example: Everyone pushed their branch to GitHub:
   git push origin feature-A
   git push origin feature-B
   git push origin feature-C
   Each developer then opened a Pull Request (PR) for their branch.

6. Reviewing and merging
   Example: Luke Egarta (Reviewer) reviewed all PRs and approved them. 
   He merged feature-A, feature-B, and feature-C into the main branch, 
   ensuring all files were combined.

7. Syncing local repositories
   Example: After merging, all members updated their local main branch:
   git checkout main
   git pull origin main
   This kept everyone’s repo aligned with the latest project version.

 Overall learning:
   By doing this activity, we saw how GitHub collaboration keeps projects organized.  
   Branching let us work on different features (A, B, C) at the same time, commits 
   documented progress, pull requests encouraged review, and merging combined 
   everyone’s contributions successfully.