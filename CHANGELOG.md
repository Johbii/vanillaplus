# Changelog
## Economy
- Removed encourage development state-edict [bf62694](https://github.com/Johbii/vanillaplus/commit/bf626943f0ab08e6f0e66d41b42bb1b37c045b49)
- Removed trade route map and Portugese trade route map flagship modifications [b61da10](https://github.com/Johbii/vanillaplus/commit/b61da1021ffcd750bd543a5df83223bd2f2f539c)
- Remove tech-cost penalty for institution not embraced [675ece3](https://github.com/Johbii/vanillaplus/commit/675ece3c6993427edb88b8d09769429a3fe0b4bd)
## Map
- Added crossable straights [8773a0c](https://github.com/Johbii/vanillaplus/commit/8773a0c0074f5a4bc074f63d0177fb2535cac616)
    - Kent -> Calais
    - Syracuse -> Malta
    - Cumbria -> Mann
- Remove native-controlled provinces for performance [9314c3c](https://github.com/Johbii/vanillaplus/commit/9314c3cde3d72e646035fca1b2126472b7b68354), [78949aa](https://github.com/Johbii/vanillaplus/commit/78949aa814db94d383ee8bec979caabc80e1238f)
- Change Ottoman map color from green to red [9c650ad](https://github.com/Johbii/vanillaplus/commit/9c650ad3d160676e2ac55de706cecb44048700ef), [71a848b](https://github.com/Johbii/vanillaplus/commit/71a848bd2c6f86314517c35eb8f9df643651aa2f)
## Random events
- Removed comet sighted event [960b224](https://github.com/Johbii/vanillaplus/commit/960b2245d44d2ee735dd17a9ca51955f301ce22c)
## War
- Shortened full-occupy warscore time for war-leader from 60 months to 24 months (x2.5) [c097e71](https://github.com/Johbii/vanillaplus/commit/c097e713fd64e45556f2ae549885a5098fb457ad)
- Tripled base garrison size from 1000 -> 3000 [7d8b62e](https://github.com/Johbii/vanillaplus/commit/7d8b62ecb41b2274f105b9bdc425cab1f3111926)<br>
    - Reduced force needed to siege fort by one-third (force needed is a calculated as a multiplier of garrison size, vanilla 1.5x -> mod 0.33x) [7d8b62e](https://github.com/Johbii/vanillaplus/commit/7d8b62ecb41b2274f105b9bdc425cab1f3111926)
    - Reduced fort maintenance cost multiplier to match vanilla values [477d348](https://github.com/Johbii/vanillaplus/commit/477d34894e56312589f95bb3700f762183791656)
- Increase base speed of ticking warscore x3 [af71d7d](https://github.com/Johbii/vanillaplus/commit/af71d7defc1f23b9a99ba8704666de20587d28c2)
- Allow declaring wars during regency [e735ad8](https://github.com/Johbii/vanillaplus/commit/e735ad82e11dbb4b8ffa242d74a02612853c5b14), [e735ad8](https://github.com/Johbii/vanillaplus/commit/ed5d4722b3e45e0ad08ba4d41dda30fd7f199765)
- Remove unconditional surrender contribution to call for peace value [adffa2b](https://github.com/Johbii/vanillaplus/commit/adffa2b7e4bf0987e9c00cbe44538f448308f759)
- Reduce cavalry combat ability from Lithuanian and Polish national ideas to 15% [f7fdf08](https://github.com/Johbii/vanillaplus/commit/f7fdf084d34edc9d5d9a4f37c7431daf32a8517b)
- Remove cavalry combat ability modifier from Cossack estate [ea2bcf4](https://github.com/Johbii/vanillaplus/commit/ea2bcf41ca522921bc0836f9cb057e692cadcbb0)
## Misc
- Added court recruitment decision [5995ed5](https://github.com/Johbii/vanillaplus/commit/5995ed599976f2a0ec0a4606220b0a4a4c7ae1a9)
    - Allows recruitment of explorers and conquistadors immediately
    - Allows recruitment of colonists after reaching diplomatic technology level 6 (or level 10 for colonial nations)
