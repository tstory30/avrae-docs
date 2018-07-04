# thieves
*By Theodore#7790.*

A way to quickly roll a Thieve's Tool check using Dexterity

### Setup
`No setup needed`

### Code
```GN
!alias thieves embed -f "**<name> makes a Thieve's Tool check!**| {{set('roll', roll('1d20'))}}1d20 ({{roll}}) + {dexterityMod + proficiencyBonus} = {{roll+dexterityMod+proficiencyBonus}}" -thumb <image>
```
