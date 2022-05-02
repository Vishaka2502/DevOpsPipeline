# Milestone 3 (Pipeline > Deployment)

## TASKS BREAKDOWN
| Task | Contibution| Issue Encountered | Resolution |
| --- | --- | --- | --- |
| provision prod instances on a cloud provider | @jlin36 |  |  |
| store prod instance information in inventory  | @jlin36 @vyadav | | |
| Deploy iTrust to the initiated production environment | @chung4 | |  |
| deployment strategy  | @vyadav | proxy issues | debugged the callback response of proxy.web |
| Create a deploy job specification in build.yml | @chung4 | | |
| Automating deploy job | @vyadav | pick both the clusters' IP dynamically | parsing the inventory file and passing info as object |
| Screencast creation | @chung4 @jlin36 | | |

#### Inventory location:
Inventory file is craeted at the root location of the repository.

### Learnings/Experiences in Milestone 2:
- Blue Green Strategy and involved proxy settings. 
- jar file creation

### Project Board:
![GitHub Project Board Screenshot](/resources/M3-Project-Board.png)

### Demo Screencast for M3
#### Screencast for Intel
[![Intel Demo](./static/Intel_M2_demo.png)](https://drive.google.com/file/d/1o2w0zNTCrzZYrTynKwT823wmWi3IahaS/view?usp=sharing "Intel Demo")<br/>
#### Screencast for M1
[![Screencast for M1]]()


#### Screencast for demo buil-green strategy
[![](./static/strategy_demo.png)](https://drive.google.com/file/d/1ZpETBf-NLtZIBU_p0goBzxt_ql5S5pon/view?usp=sharing)