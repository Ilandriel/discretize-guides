---
title: "Power Daredevil"
date: "2018-07-01"
group: "Good Builds"
role: "Damage"
profession: "Thief"
specialization: "Daredevil"
benchmark: { small: { dps: 34815, by: "Ramirez [SC]", youtube: "v503BIZmaME" }}
skills: [13132, 13014, 13044, 13065, 13025]
traits: [2047]
conditions: ["Vulnerability","Crippled","Blind","Weakness"]
effects: ["Stealth"]
---

The <Specialization name="thief"/> profession is really behind the other power based builds like <Specialization name="dragonhunter" prefix="power"/> and <Specialization name="weaver" prefix="power"/> dps wise, but if you really have nothing else it is fine for off-meta groups. It has a very simple rotation and offers great mobility for skips, as well as endless party <Effect name="stealth"/> (though even a <Specialization name="druid"/> fills this role perfectly).

While <Specialization name="deadeye" prefix="power"/> is more efficient in raids, <Specialization name="daredevil" prefix="power"/> is better in fractals.

<Divider>
Equipment
</Divider>

<Grid>
<Column>
<Armor helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</Column>

<Column>
<Weapons weapon1MainId="46773" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Staff" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card>
<CardHeader>
Alternative weapons
</CardHeader>
<CardContent>
* Staff with <Item id="36053" text="false"/> / <Item id="24615" text="false"/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
* A Shortbow to blast <Boon name="might"/>
</CardContent>
</Card>
</Column>

<Column>
<Trinkets backItemId="49384" backItemStatId="584" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</Column>
</Grid>

<Divider>
Build
</Divider>

<Grid>
<Column width="9">
<Traits title="" traits1Id="28" traits1="Dreadly Arts" traits1Selected="1276,1292,1269" traits2Id="35" traits2="Critical Strikes" traits2Selected="1268,1272,1904" traits3Id="7" traits3="Daredevil" traits3Selected="1933,1884,2047"/>
</Column>

<Column>
<Skills weapon1Skill1="" weapon1Skill2="" weapon1Skill3="" weapon1Skill4="" weapon1Skill5="" utilitySkill1="30400" utilitySkill2="13037" utilitySkill3="30868" utilitySkill4="13046" utilitySkill5="13132"/>

<Card>
<CardHeader>
Situational
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="13117" size="big" text="false"/> | Group stealth. |
| <Skill id="13065" size="big" text="false"/> | Drop it to blast <Effect name="stealth"/> for skips or destroy projectiles. |
| <Skill id="13002" size="big" text="false"/> | 1200 range teleport, use it again to teleport back. |
| <Skill id="13044" size="big" text="false"/> | 3 seconds AoE <Effect name="stealth"/> (also another blast). |
</CardContent>
</Card>
</Column>
</Grid>

<Divider>
Details
</Divider>

<Grid>
<Column width="9">
<Card>
<CardHeader>
Rotation
</CardHeader>
<CardContent>
* Dodge
* <Skill id="30868"/> => <Skill id="30693"/> (repeat from here)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> => <Skill id="30434"/>
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> => <Skill id="30434"/>
* <Skill id="29911"/> (Staff 2)
* <Skill id="30614"/> => <Skill id="30135"/> (Staff 1)
* Dodge
* <Skill id="30434"/> (Staff 1)
* Repeat

You can also activate <Skill id="13046"/> for the last few attacks of a fight.
</CardContent>
</Card>
</Column>

<Column>
<Card>
<CardHeader>
CC skills
</CardHeader>
<CardContent>
| | |
| -- | -- |
| <Skill id="30693"/> | 200 damage |
| <Skill id="13132"/> | 150 Defiance bar damage per ally |
</CardContent>
</Card>
<Video videoId="v503BIZmaME" videoTitle="Daredevil Staff 34.8k by Ramirez [SC]"/>
</Column>
</Grid>