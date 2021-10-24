# Among us 4: new 9 roles
![버전 1](https://user-images.githubusercontent.com/93028495/138575847-7116f508-e7a6-4fbd-b1d6-9ec3ce792507.png)
version 1


**version 1 roles:**<br/>
- [Medic](#medic)
- [Sheriff](#sheriff)
- [Engineer](#engineer) 
- [Cat](#cat) 
- [Jester](#jester) 
- [Survivor](#survivor) 
- [Janitor](#janitor) 
- [Morphling](#morphling) 
- [Blackmailer](#blackmailer) 

-----------------------
# Roles
# version 1 roles
## Medic
![1 의사](https://user-images.githubusercontent.com/93028495/138575578-26ce10ec-8212-4623-a5d5-d14564e25109.png)
### **Team: Crewmate**
The Medic is a Crewmate who can give 1 player a shield that will make them immortal until the Medic dies. A Shielded player cannot be Shifted into, Hacked or Killed by anyone, unless by suicide. They can also revive a dead body. If the Medic reports a dead body, they can get a report containing clues to the Killer's identity. A report can contain the name of the killer or the color type (Darker/Lighter).

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Medic | The percentage probability of the Medic appearing | 0%~100% | 0% |
| Show Shielded Player | Who should be able to see who is Shielded | Self / Medic / Self + Medic / Everyone | Self |
| Show Medic Reports | Whether the Medic gets information when reporting a body | True/False | True |
| Time Where Medic Reports Will Have Name | If a body has been dead for shorter than this amount, the Medic's report will contain the killer's name | 5s~15s | 0s |
| Time Where Medic Reports Will Have Color Type | If a body has been dead for shorter than this amount, the Medic's report will have the type of color | 10s~60s | 15s |
| Who gets murder attempt indicator | Who will receive an indicator when someone tries to Shift into, Hack or Kill them | Medic / Shielded / Everyone / Nobody | Medic |
| Shield breaks on murder attempt | Whether the Shield breaks when someone attempts to Shift into, Hack or Kill them | True/False | False |
| Revive cooldown | The Cooldown of reviving | 5s~60s | 10s |

-----------------------
## Sheriff
![2 보안관](https://user-images.githubusercontent.com/93028495/138575590-d52a1008-48a9-45fa-bd47-26051c4ecf86.png)
### **Team: Crewmate**
The Sheriff is a Crewmate who can kill the Impostors. However, if they kill a Crewmate or a Neutral player they can't kill, they instead die themselves.

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Sheriff | The percentage probability of the Sheriff appearing | 0%~100% | 0% |
| Show Sheriff | Whether everybody can see who the Sheriff is | True/False | False |
| Sheriff Miskill Kills Crewmate | Whether the other player is killed if the Sheriff Misfires | True/False | False |
| Sheriff Kills Jester | Whether the Sheriff is able to kill the Jester | True/False | False |
| Sheriff Kills serial killer | Whether the Sheriff is able to kill serial killer | True/False | False |
| Sheriff Kills Arsonist | Whether the Sheriff is able to kill the Arsonist | True/False | False |
| Sheriff Kills plague bearer | Whether the Sheriff is able to kill the plague bearer | True/False | False |
| Sheriff Kill Cooldown | The cooldown of Sheriff's killing | 10~60s | 25s |
| Sheriff can report who they've killed | Whether the Sheriff is able to report their own kills | True/False | True |

-----------------------
## Engineer
![3 기술자](https://user-images.githubusercontent.com/93028495/138575594-c98c2bf1-dfaf-4242-b218-ed2d305557dc.png)
### **Team: Crewmate**
The Engineer is a Crewmate who can fix sabotages easily, and fix sabotages in anywhere. They can use vents to get across the map easily.

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Engineer | The percentage probability of the Engineer appearing | 0%~100% | 0% |
| Engineer Fix Per | Whether the Engineer can fix 1 sabotage per round or per game | None / Round / Game | Round |
| Engineer Fix Cooldown | The cooldown of Engineer's fixing sabotage | 10~60s | 25s |

-----------------------
## Cat(town of roles member's idea 1)
![4 고양이](https://user-images.githubusercontent.com/93028495/138575599-584232b1-986d-48dd-abbe-35304bcfa8bb.png)
### **Team: Crewmate**
The Cat is a Crewmate who can track the location of some people. They have a long protect Cooldown, but if They protect player who their owner has targeted, Their protect cooldown decreases. They don't die.

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Cat | The percentage probability of the Cat appearing | 0%~100% | 0% |
| Owner | The percentage probability of the Owner appearing | 0%~100% | 0% |
| Cat protect cooldown decrease by: | - | 5s~30s | 10s |
| How many player can be tracked by cat | The number of player cats can track | 1~5 players | 2 players |
| cat count | The number of cats | 1~2 players | 1 player |

-----------------------
## Jester
![1 어릿광대](https://user-images.githubusercontent.com/93028495/138575605-ccefd29b-586f-4356-8c7e-bc560001c670.png)
### **Team: Neutral evil**
wining : being ejected
|Name|Description|Range|Default|
|---|---|---|---|
|Chance|The percentage probability of the Jester appearing|0%-100%|0%|

-----------------------
## Survivor
![2 생존자](https://user-images.githubusercontent.com/93028495/138575617-f006b825-292d-41d6-a2d3-5aa900ce7cb1.png)
### **Team: Neutral benign**
wining : surviving the game\
if survivor as long as survived, they will win with winner.
|Name|Description|Range|Default|
|---|---|---|---|
|Chance|The percentage probability of the Survivor appearing|0%-100%|0%|

-----------------------
## Janitor
![1 관리인](https://user-images.githubusercontent.com/93028495/138575625-175e4ae7-5e9f-4632-973f-914c68f07e1d.png)
### **Team: Impostor**
The Janitor is an Impostor who can clean up bodies. Both their Kill and Clean ability have a shared cooldown, meaning they have to choose which one they want to use.

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Janitor | The percentage probability of the Janitor appearing | 0%~100% | 0% |

-----------------------
## Morphling(To)
![2 변장자](https://user-images.githubusercontent.com/93028495/138575860-6e7483f5-98c0-4e0a-825c-4164b0946bdd.png)
### **Team: Impostor**
The Morphling is an Impostor who can Morph into another player. At the beginning of the game and after every meeting, they can choose someone to Sample. They can then Morph into that person at any time for a limited amount of time. To balance the role, they can't use vent while disguise.

### Game Options
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Morphling | The percentage probability of the Morphling appearing | 0%~100% | 0% |
| Morph Cooldown | The cooldown of Morphing | 10~60s | 10s |
| Morph Duration | How long the Morph lasts for | 10~180s | 180s |

-----------------------
## Blackmailer
![3 협박자](https://user-images.githubusercontent.com/93028495/138575660-5b25ccdb-51cb-4428-af96-9703b064d57c.png)
### **Team: Impostor**
The Blackmailer is an Impostor who can blackmail 1~3 players in only 1 round. When a meeting begins the blackmailed player will get an alert that they are blackmailed and cannot access the chat to communicate with others.
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Blackmailer | The percentage probability of the Blackmailer appearing | 0%~100% | 0% |
| Blackmail Cooldown | The cooldown of Blackmailing | 10~60s | 10s |
| How many player can be Blackmailed in 1 round | The number of player Blackmailer can Blackmail in 1 round | 1~3 players | 1 player |
| Blackmailed Duration | How long Blackmailing lasts for | 1~2 round | 1 round |
