## Overlay Setup

![Step One](https://i.imgur.com/kOUcZvi.png)

![Step...rest of them](https://i.imgur.com/XpMdsHw.png)

![Okay last step](https://i.imgur.com/5Zn9Icy.png)

## Mod Commands
```
!addxp 
${user} - you have added ${1:} XP giving you a total of ${count xp '+${1}'}

!removexp 
${user} - you have removed ${1:} XP giving you a total of ${count xp '-${1}'}

!resetxp 
${user} - you have reset the overall XP to ${count xp 0}

!setlvlxp
${user} - you have set ${count lvlxp ${1:}} as the XP required for the next level.
```

## Everyone Commands

```
!xp
${user} - YourName needs ${customapi.https://twitch.center/customapi/math?expr=${getcount lvlxp}} XP until the next level.
```

## Command Usage

Once your commands are setup and you are ready to start using it, the first step is setting your current ***Level XP***. Head to your Overall tab and enter in the amount of experience your PMC has. For this exmaple, we'll use 3,373,425 XP. 

You type: `!setlvlxp 3373425`

StreamElements should respond: `@Username - you have set 3373425 as the XP required for the next level.`

After that, you are ready to start `adding xp` with the `!addxp` command. Ex: `!addxp 27452` when the raid is over and you see how much XP was earned during that raid. 

In the event of a mistake, just use `!removexp Amount` to fix your mistake. 

At the end of your stream or at the start of your next stream, simply hit the `!resetxp` command to set XP to `0` and then `!setlvlxp` with your new XP level of the day!
