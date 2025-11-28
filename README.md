# boardwalk-games

A dummy 'client-build' to exercise project planning and sound devOps knowledge. This focuses on tracking user stories to implement client requriements through github projects with custom labels and issue templates.


# Project planning
Creating a kanban board with user stories enables us to best track feature requests and clearly defines acceptance criteria. Custom labels for MoSCoW prioritisation help sprint planning whilst still being able to compare priority of must-have issues.
<img width="1262" height="847" alt="image" src="https://github.com/user-attachments/assets/e34d3bd2-101a-4032-993b-4bca7b38cc61" />


# Testing
Following smoke testing, lighthouse report is as follows
<img width="932" height="1244" alt="image" src="https://github.com/user-attachments/assets/ab0ace98-9ce3-4543-aea2-2b069a3c6d41" />

Whilst performance scores could be improved, the largest contributors in performance loss come from hosting through github pages.
<img width="540" height="826" alt="image" src="https://github.com/user-attachments/assets/46515793-4bec-4655-8169-13d09b4217b4" />

Other performance suggestions point to external libraries used (google fonts and bootstrap), and have no actions required. 
Tangible performance improvements we can make include using separate, lower quality image sizes for our small screen breakpoints, but with a industry wide rise in PPI for mobile device screens it would be preferable to search for optimisations elsewhere. 

Re-running lighthouse in desktop mode shows a sizeable performance improvement:
<img width="553" height="1288" alt="image" src="https://github.com/user-attachments/assets/4bf14e63-a938-40bf-bef0-30827366ccdc" />

but highlights missing alt attributes on one image. Fixing this bug, our accessibility and best practices score are both 100/100.
