# Among us 4: new 18 roles
![버전 1](https://user-images.githubusercontent.com/93028495/138575847-7116f508-e7a6-4fbd-b1d6-9ec3ce792507.png)
this is version 1 of Among us 4.
![버전 2](https://user-images.githubusercontent.com/93028495/138583975-cfa29af4-afaa-417e-ae6e-afb38d48d194.png)
this is version 2 of Among us 4.
![버전 3](https://user-images.githubusercontent.com/93028495/138583983-ad5fcc26-4a70-4599-9e65-dbd4e3e28524.png)
this is version 3 of Among us 4.
![버전 4](https://user-images.githubusercontent.com/93028495/138585089-39ad1adc-9f72-4b40-8155-adad51658d21.png)
this is version 4 of Among us 4.
![버전 5](https://user-images.githubusercontent.com/93028495/138587530-4f6d6f6f-70d4-426b-8b48-aea173196114.png)

this is version 4 of Among us 4.
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

**version 2 roles:**<br/>
- [Executioner](#executioner)
- [Yandere](#yandere)
- [Serial killer](#serial-killer)
- [Arsonist](#arsonist)
- [Glitch](#glitch)

**version 3 roles:**<br/>
- [Guardian](#guardian)
- [Swapper](#swapper)
- [Mayor](#mayor)
- [Dictator](#dictator)

**version 4 roles:**<br/>
- [Phoenix](#phoenix)
- [Spirit](#spirit)
- [Anti tasker](anti-tasker)
- [Crewstor](#crewstor)

**version 5 roles:**<br/>
- [Investigator](#investigator)
- [Mentalist](#mentalist)
- [Student president](#student-president)
- [Witch](#witch)
- [Poisoner](#poisoner)
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
## Cat
![4 고양이](https://user-images.githubusercontent.com/93028495/138575599-584232b1-986d-48dd-abbe-35304bcfa8bb.png)
**sunny6386's idea**
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
win condition: being ejected
|Name|Description|Range|Default|
|---|---|---|---|
|Chance|The percentage probability of the Jester appearing|0%-100%|0%|

-----------------------
## Survivor
![2 생존자](https://user-images.githubusercontent.com/93028495/138575617-f006b825-292d-41d6-a2d3-5aa900ce7cb1.png)
### **Team: Neutral benign**
win condition: surviving the game\
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
## Morphling
![2 변장자](https://user-images.githubusercontent.com/93028495/138575860-6e7483f5-98c0-4e0a-825c-4164b0946bdd.png)
**sunny6386's idea**
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
| Blackmailing Duration | How long Blackmailing lasts for | 1~2 round | 1 round |

-----------------------
# version 2 roles
## Executioner
![3 사형 집행인](https://user-images.githubusercontent.com/93028495/138578527-ad85a2ab-2911-462c-bdec-092327779bb5.png)
### **Team: Neutral evil**
win condition: getting their target ejected
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Executioner | The percentage probability of the Executioner appearing | 0%~100% | 0% |
| Executioner becomes on Target Dead | Which role the Executioner becomes when their target dies | Crewmate / Jester | Crewmate |

-----------------------
## Yandere
![4 집착증자](https://user-images.githubusercontent.com/93028495/138578534-d98982cc-c01e-40b6-af8c-277fa761f4a0.png)
### **Team: Impostor**
Yandere is an Impostor who can make 1 player their member or kill. Yandere's member is Yanderate. 
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Yandere | The percentage probability of the Yandere appearing | 0%~100% | 0% |
| Yandere member count | number of Yandere member count | 1~2 players | 1 player |

-----------------------
## Serial killer
![1 연쇄 살인마](https://user-images.githubusercontent.com/93028495/138580964-bd2fe38f-70b3-4794-a626-8f61e6031d24.png)
### **Team: Serial killer**
win condition: killing all crewmates and impostors
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Serial killer | The percentage probability of the Serial killer appearing | 0%~100% | 0% |
| Serial killer can use vent | whether the serial killer can use vent | True/ | 1 player |
| Serial killer count | number of Serial killer count | True/False | False |

-----------------------
## Arsonist
![2 방화범](https://user-images.githubusercontent.com/93028495/138580970-2852d4b9-7775-4667-8e1a-357fc8bea9c9.png)
### **Team: Serial killer**
The Arsonist is a Serial killer who can douse other players.\
Once they have doused every player remaining, they can Ignite everyone at once.\
Upon Igniting every player, they win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Arsonist | The percentage probability of the Arsonist appearing | 0%~100% | 0% |
| Douse Cooldown | The cooldown of the Arsonist's Douse button | 10s~60s | 10s |
| Arsonist count | number of Arsonist count | True/False | False |

-----------------------
## Glitch
![3 글리치](https://user-images.githubusercontent.com/93028495/138583305-3e496e53-9acb-42b6-b06f-9fe13098eb11.png)
### **Team: Serial killer**
The Glitch is a Serial killer who can Hack players. hacked player can't report bodies and do tasks.\
Hacking prevents the hacked player from doing anything but walk around the map.\
The Glitch can Mimic someone, which results in them looking exactly like the other player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| The Glitch | The percentage probability of The Glitch appearing | 0%-100% | 0% |
| Mimic Cooldown | The cooldown of The Mimic | 10s~60s | 30s |
| Mimic Duration | How long The Glitch can Mimic a player | 10s~60s | 10s |
| Hack Cooldown | The cooldown of The Glitch's Hack button | 10s~60s | 30s |
| Hack Duration | How long The Glitch can Hack a player | 10s~60s | 10s |
| Glitch Kill Cooldown | The cooldown of the Glitch's Kill button | 10s~60s | 30s |
| Initial Glitch Kill Cooldown | The cooldown of The Glitch's Kill button at the start of a game | 10s~60s | 10s |
| Glitch Hack Distance | How far away The Glitch can Hack someone from | Short / Normal / Long | Short |

------------------------
# version 3 roles
## Guardian
![5 경호원](https://user-images.githubusercontent.com/93028495/138583400-4828fac4-c3de-4c40-8121-6aba88b9bbda.png)
### **Team: Crewmate**
The Guardian is a crewmate who can protect any player they wish for 1 round. In those 10 rounds, any attack towards the player is negated. Any player that tried to attack them will have their ability put back on cooldown, but it will have had no effect.
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Guardian | The percentage probability of The Guardian appearing | 0%-100% | 0% |
| Protect Cooldown | The cooldown of The Protecting other player | 10s~60s | 30s |
| Protect Duration | How long The Guardian can Protect a player | 10s~90s/1 round | 1 round |

-----------------------
## Swapper
![6 운명술사](https://user-images.githubusercontent.com/93028495/138583790-de234251-8d24-4dd1-a9bf-f6e25db318bd.png)
### **Team: Crewmate**
The Swapper is a Crewmate who activates in meetings. The Swapper can swap votes of 2 players and change who potentially gets voted out. However, if none of the Swapper's targets gets voted out, then the 2 players will switch bodies for the next round, changing how they look and their name. Once the next meeting starts, they will change place.
| Name | Description | range | Default |
|----------|:-------------:|:------:|:------:|
| Swapper | The percentage probability of the Swapper appearing | 0%~100% | 0% |

-----------------------
## Mayor
![7 시장](https://user-images.githubusercontent.com/93028495/138583858-d523a724-e971-4a14-9dfd-9f094833fc24.png)
### **Team: Crewmate**
The Mayor is a Crewmate who can vote multiple times.\
The Mayor has a Vote Bank, which is the number of times they can vote.\
They have the option to abstain their vote during a meeting, adding that vote to the Vote Bank.\
As long as not everyone has voted, the Mayor can use as many votes from their Vote Bank as they please.
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Mayor | The percentage probability of the Mayor appearing | 0%~100% | 0% |
| Mayor's Vote |  | 2~5 votes | 2 votes |
| Mayor Votes Show Anonymous | Whether the Mayor's extra votes will show up anonymously | True/False | False |

------------------------
## Dictator
![8 독재자](https://user-images.githubusercontent.com/93028495/138583865-e855d924-5118-4aa6-be64-ae61caf8ea54.png)
### **Team: Crewmate**
The Dictator's opportunities make dictator able to kill 1 player at one meetings.(But dictator can't use their opportunities in two day in a row.)
settings
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| dictator | The percentage probability of the dictator appearing | 0%~100% | 0% |
| dictator's opportunities | number of dictaor's opportunities | 5~50 opportunities | 50 opportunities |

-------------------------
# version 4 roles
## Phoenix
![9 불사신](https://user-images.githubusercontent.com/93028495/138585431-9a9bf897-4a29-461e-9861-610398d38aa9.png)
the phoenix is a Crewmate who can revive so as to be able to bring back 1 ghost per 1 round or kill 1 player(but if it's impostor, they can kill again) or reveal their name for 5 seconds. they can be cleansed.
settings
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Phoenix | The percentage probability of the Phoenix appearing | 0%~100% | 0% |
| Phoenix revive per | Whether the Phoenix can revive ghost per round or per game | None/Round/game | Round |
| Phoenix kill cooldown | The cooldown of Phoenix's killing | 0s~30s | 0s |
| Phoenix reveal duration | The duration of Phoenix's revealing | 5s~10s | 5s |
| Phoenix reveal | The duration of Phoenix's revealing | 5s~10s | 5s |

-------------------------
## Spirit
![10 스피릿](https://user-images.githubusercontent.com/93028495/138586230-dea19397-9774-4bc0-9d12-cdab5fda7c4f.png)
The spirit can't be voted out until only 3 player survive in the game. they can't be killed by sheriff until only 3 player survive in the game.
settings
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Spirit | The percentage probability of the Spirit appearing | 0%~100% | 0% |

-------------------------
## Anti tasker
![5 속박자](https://user-images.githubusercontent.com/93028495/138586296-033bad89-c53b-44f8-9034-f87f01218d69.png)
The Antitasker is an Impostor who once per round, they can block a player from doing their tasks. A taskblocked player will be unable to complete their tasks or fix any sabotage, until a meeting is called.
setting
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Anti tasker | The percentage probability of the Anti tasker appearing | 0%~100% | 0% |
| Taskblock Cooldown | The cooldown of Taskblocking | 10~60s | 10s |
| How many player can be Taskblocked in 1 round | The number of player Blackmailer can Taskblock in 1 round | 1~3 players | 1 player |
| Taskblocking Duration | How long Blackmailing lasts for | 1~2 round | 1 round |

-------------------------
## Crewstor
![6 크루스터](https://user-images.githubusercontent.com/93028495/138586300-6c8b3831-5b8a-4366-9a72-8eb64d576837.png)
The crewstor is an impostor who can do tasks for impostor's victory.
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Crewstor | The percentage probability of the Crewstor appearing | 0%~100% | 0% |
| Crewstor's tasks | The number of Crewstor's tasks | 10~30 tasks | 10 tasks |

------------------------
# version 4 roles
settings
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Witch is Impostor | Whether witch is Impostor | 0%~100% | 0% |

## Investigator
The Investigator is a Crewmate who finishes their tasks so as to be able to investigate the role of any player. However, if the player is Neutral or Impostor, they will also see who the Investigator is. If the Investigator investigates an Angel, and their target is an Impostor, the Angel will also show as an Impostor. Likewise if they are a crewmate, the Angel will also show as a crewmate. The Investigator also gets false readings from Neutral roles. If they investigate the Executioners target, it will display the same reading as an executioner. If they investigate a doused player, it will give the same reading as an Arsonist, and if they investigate and infected player, it will give the same reading as the Plaguebearer.
settings
| Name | Description | Range | Default |
|----------|:-------------:|:------:|:------:|
| Investigator | The percentage probability of the Investigator appearing | 0%~100% | 0% |
| finish tasks first | whether The Investgator Must finish their tasks so as to Investigate role of other player | True/False | True |
