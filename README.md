# Artifact-Gen
An artifact can be either A flower, a feather, a sands, a goblet, and a circlet.

an artifact has a main stat and a secondary stat. if a stat is already a mainstat, it cannot appear in the same piece as a substat. 

the stats that can appear as a substats are : flat hp, flat atk, flat def, hp%, atk%, def%, EM, ER, crit rate, and crit damage

for a flower, it is always a flat hp main stat

for a feather, it is always a flat atk main stat

a sands can have 5 possible main stats : atk%, def%, hp%, EM, and ER. The chances of dropping an atk%, def%, or hp% is 26.6%. while the chance of dropping an EM or ER sands is 10%

for the goblet it can have 11 possible main stats : atk%, def%, hp%, EM, Anemo DMG Bonus, Geo DMG Bonus, Pyro DMG Bonus, Cryo DMG Bonus, Hydro DMG Bonus, Electro DMG Bonus, and Dendro DMG Bonus. The chance of dropping an atk% or hp% goblet is 19.25%. the chance of dropping def% is 19%, the chance of dropping every DMG Bonus cup goblet is 5%, and the chance to drop an EM goblet is 2.5%

for the circlet, it can have 7 main stats : atk%, def%, hp%, healing bonus, crit rate, crit damage, and EM. the chance of dropping an atk%, def%, or hp% circlet is 22%, the chance of crit rate, crit damage, and healing bonus is 10% and the chance for EM is 4%

an artifact substat can start at level 0 with having either 3 or 4 substats. an artifact has a 80% chance to start with 3 substats and a 20% chance to start with 4 substats 

when an artifact is generated it starts at level 0 and can be leveled until level 20. at level 4, 8, 12, 16, and 20, an artifact substat gets upgraded. in the case of artifact that start with 3 substats, an additional substat will be added at level 4.

when generating an artifact, the possible substats generated are assigned to a number representing its weighted probability as follows :
flat hp, flat atk, and flat def = 6
atk%, def%, hp%, em, er = 4
crit rate and crit damage = 3

when artifact substats are generated, there are 4 possible values for each given substat. each value has an equal probability of being generated (25% chance) as follows : 

atk% and hp% = 4.1, 4.7, 5.3, 5.8
def% = 5.1, 5.8, 6.6, 7.3
flat atk = 14, 16, 18, 19
flat def = 16, 19, 21, 23
flat hp = 209, 239, 269, 299
em = 16, 19, 21, 23
er = 4.5, 5.2, 5.8, 6.5
crit rate = 2.7, 3.1, 3.5, 3.9
crit damage = 5.4, 6.2, 7, 7.8
