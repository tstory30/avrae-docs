# herb
*By Theodore#7790.*

A way to quickly roll a Herbalism Kit check using Wisdom

### Setup
`No setup needed`

### Code
```GN
!servalias herb embed -f "**<name> makes a Herbalism Kit check!**| {{set('roll', roll('1d20'))}}1d20 ({{roll}}) + {wisdomMod + proficiencyBonus} = {{roll+wisdomMod+proficiencyBonus}}" -thumb <image>
```
