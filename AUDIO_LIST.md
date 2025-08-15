Credits to:  
❕토 Tobi 비❕ / BruhLookAtThis (https://linktr.ee/BruhLookAtThis)  


/*--------------------------------------------------INTRO-TO-LOGS--*/  
/*--------------------------------------------------INTRO-TO-LOGS--*/  
/*--------------------------------------------------INTRO-TO-LOGS--*/  
THIS IS A LIST OF IDENTIFIED SOUND FILES AND A BRIEF EXPLANATION ON WHEN THEY ACTIVATE   

- NOTE 1: Many Sounds Are Affected By Random Pitch Changes  
- NOTE 2: These Sounds Were Not Heavily Tested, So They May Activate In More Instances Than Written  
          - Feel free to correct me on any mistakes
  
- NOTE 3: Some Annotations, like "Always Plays", Maybe Be Missing From A Few Entries. My Fault Lol  
- NOTE 4: Files with "Cue" in their name arent actual soundfiles. Im moving them to the very bottom of this file  
          - FIRSTLY:  
            - I tweaked Option 0 of my tool to remove any cue files when processing for Option 0 (This needs to be re-implemented as of v0.0.6)  
            - Hopefully this prevents people from trying to use them, as I dont think its good practice to  
          - SECONDLY: (Just leaving this here for information purposes)  
            - Oddly, they can still be replaced with sound files, and it will play ingame  
            - BUT I recommend you dont do that because they overlap with actual sound files  
            - On top of that, they ignore volume levels in your settings  
            - I.e. even if you set music/voice/sfx volume to zero, these replaced Cue files will still play audio  
            - If you view them in FModel, their metadata will point to relevant sound file(s)
  
- NOTE 5: Some BGMs, especially BOSS BGMs, require more sophisticated setup in Unreal Engine  
          - This includes linking them to Cue files, and/or adding Concatenator Nodes to those Cue files (to connect Intros & Loops to a single Cue)  
          - I have only logged this warning for files in which I have personally set up Cues for, so be aware the song you replace may need one  
          - I have added warnings for those I suspect may require Cues, but I have not tested for sure so I cannot be certain  
          - I honestly think its always a safe option to just make a Cue file though if you see that a BGM has one in FModel  

/*-------------------------------------------------BGM--*/  
/*-------------------------------------------------BGM--*/  
/*-------------------------------------------------BGM--*/  

/*GENERAL BGM*/  

-BGM_SYS_TITLE_01 = Title Screen Music  
-BGM_SYSTEM_TRAININGROOM = Training Room OST  
-BGM_NIER_EMIL_ON = Emil Truck Default Music  
-BGM_NIER_EMIL_OFF = Emil Truck Default Music  

/*CAMPS BGM*/  

-BGM_CAMP_MV1_ON = Camp Song (Song Of The Sirens)  
-BGM_CAMP_MV1_OFF = Camp Song (Song Of The Sirens)  
-BGM_CAMP_MV2_ON = Camp Song (Song Of The Nomad)  
-BGM_CAMP_MV2_OFF = Camp Song (Song Of The Nomad)  
-BGM_CAMP_MV3_ON = Camp Song (Song Of The Wanderer)  
-BGM_CAMP_MV3_OFF = Camp Song (Song Of The Wanderer)  
-BGM_CAMP_MV4_ON = Camp Song (Song Of The Traveler)  
-BGM_CAMP_MV4_OFF = Camp Song (Song Of The Traveler)  
-BGM_CAMP_YJ1_Lullaby_of_Secret_ON = Camp Song (Lullaby of Secret)  
-BGM_CAMP_YJ1_Lullaby_of_Secret_OFF = Camp Song (Lullaby of Secret)  
-BGM_CAMP_YJ2_Just_Fine_ON = Camp Song (Just Fine)  
-BGM_CAMP_YJ2_Just_Fine_OFF = Camp Song (Just Fine)  
-BGM_CAMP_YJ3_Blur_ON = Camp Song (Blur)  
-BGM_CAMP_YJ3_Blur_OFF = Camp Song (Blur)  

/*DESERT - SOLAR NOT ACTIVATED BGM*/  

-BGM_DESERT_UNDISCOVER_143 = Desert Solar Not Activated Default Music  
-BGM_DESERT_UNDISCOVER_INTRO_143 = Desert Solar Not Activated Intro Music  

/*DESERT - OASIS BGM*/  

-BGM_E05_EVENT_OASIS_SUMMER = Desert Oasis Area Summer Music  
-BGM_E05_EVENT_OASIS_SUMMER_CAMP =   
-BGM_E05_EVENT_OASIS_SUMMER_MONO = Desert Oasis Area Summer Music (Mono Track)  

/*DESERT - BOSS SHAEL BGM*/  

-BGM_DESERT_BOSS_SHAEL_INTRO [Requires a Cue with Concatenator Node]  
-BGM_DESERT_BOSS_SHAEL_LOOP [Requires a Cue with Concatenator Node]  

/*DESERT - SOLAR ACTIVATED BGM*/  

-BGM_DESERT_P3_INTRO = Desert Solar Activated Intro Music  
-BGM_DESERT_P3_LOOP = Desert Solar Activated Default Music  
-BGM_DESERT_P3B_LOOP = Desert Solar Activated Battle Music (???)  
-BGM_DESERT_BATTLE_N3 = Desert Battle Music (With Tall Caped Robot)  

/*DESERT - ABYSS LEVOIRE BGM*/  

-BGM_EVENT_ESCAPE_WAVE = Desert Abyss Levoire Fan Saw Area Default Music  
-BGM_LAB2_ZONE_01_BATTLE = Desert Abyss Levoire Early Area Battle Music  
-BGM_LAB2_ZONE_01_DEFAULT = Desert Abyss Levoire Early Area Default Music  
-BGM_LAB_ZONE02 = Desert Abyss Levoire Spinning Laser Room Mini Challenge Area Default Music  
-BGM_LAB2_ZONE_02_BATTLE = Desert Abyss Levoire Second Area Battle Music (???)  
-BGM_LAB2_ZONE_02_DEFAULT = Desert Abyss Levoire Second Area Default Music (???)  

/*EDIOS 7 - EARLY AREA BGM*/  

-BGM_DED_ZONE_01_DEFAULT = Eidos 7 Default Music  
-BGM_DED_ZONE_01_DEFAULT_V_144 = Eidos 7 Default Music (???)  
-BGM_DED_ZONE_01B_DEFAULT = Eidos 7 Default Music (???)  
-BGM_DED_ZONE_01_BATTLE = Eidos 7 Combat Music  

/*EDIOS 7 - CLOCK AREA BGM*/  

-BGM_DED_ZONE_05_DEFAULT = Eidos 7 Clock Area Default Music  
-BGM_DED_ZONE_05_BATTLE = Eidos 7 Clock Area Battle Music  

/*EDIOS 7 - AFTER TRAIN AREA BGM*/  

-BGM_DED_ZONE_04_DEFAULT_INTRO = Eidos 7 After Train Area Intro Music  
-BGM_DED_ZONE_04_DEFAULT_LOOP = Eidos 7 After Train Area Default Music  


/*MATRIX 11 BGM*/  

-BGM_ME_ZONE_01_Battle = Matrix 11 Battle Music   
-BGM_ME_ZONE_01_Default = Matrix 11 Default Music   
-BGM_ME_ZONE_02_BATTLE = Matrix 11 Battle Music   
-BGM_ME_Zone_02_Default = Matrix 11 Default Music   
-BGM_ME_ZONE_03_BATTLE = Matrix 11 Battle Music   
-BGM_ME_ZONE_03_BATTLE2 = Matrix 11 Battle Music   
-BGM_ME_Zone_03_Default = Matrix 11 Default Music  
-BGM_Matrix_XI_Field_TrashBattle_Loop = Matrix 11 Battle Squid Men Music (???)  
-BGM_ME_EVENT_BATTLE_N3_INTRO = Matrix 11 Battle Squid Men Intro Music   
-BGM_ME_EVENT_BATTLE_N3_LOOP = Matrix 11 Battle Squid Men Music  
-BGM_Dystopia_Peace = Matrix 11 Infected Train Bridge Area Default Music   

/*MATRIX 11 - BOSS STALKER BGM*/  

-BGM_ME_BOSS_STALKER_PRE_INTRO_170 = Intro Cutscene OST For Stalker Boss Challenge  
-BGM_ME_BOSS_STALKER_P1_INTRO_170  
-BGM_ME_BOSS_STALKER_P1_LOOP_170 [Requires a Cue]  
-BGM_ME_BOSS_STALKER_P2_INTRO_170  
-BGM_ME_BOSS_STALKER_P2_LOOP_170 [Requires a Cue]  

/*MATRIX 11 - LOWER SEWER BGM*/  

-BGM_ME_ZONE_04_BATTLE = Matrix 11 Lower Sewer Area Battle Music  
-BGM_ME_Zone_04_Default = Matrix 11 Lower Sewer Area Default Music  
-BGM_ME_EVENT_SHELTER_LOOP = Matrix 11 Abandoned Shelter Area Default Music  

/*MATRIX 11 - BOSS JUGGERNAUT BGM*/  

-BGM_ME_BOSS_JUGGERNAUT_BELIAL_P1 = Matrix 11 Juggernaut Boss Fight Music Part 1 [Requires a Cue]  
-BGM_ME_BOSS_JUGGERNAUT_BELIAL_P2 = Matrix 11 Juggernaut Boss Fight Music Part 2 [Requires a Cue]  
-BGM_ME_BOSS_JUGGERNAUT_FINISH = Matrix 11 Juggernaut Boss Fight Music End [Requires a Cue]  

/*MATRIX 11 - SUBMERGED TRAIN YARD BGM*/  

-BGM_ME_ZONE_05_DEFAULT = Matrix 11 Submerged Train Yard Area Default Music  
-BGM_ME_ZONE_05_UNDERWATER = Matrix 11 Submerged Train Yard Area Default Music (Underwater)  
-BGM_ME_ZONE_05_INTRO = Matrix 11 Submerged Train Yard Area Intro Music  

/*MATRIX 11 - POST-SAWBLADE SLIDE QTE BGM*/  

-BGM_ME_Zone_06_Battle = Matrix 11 Post Saw QTE Area Battle Music  
-BGM_ME_Zone_06_Default = Matrix 11 Post Saw QTE Area Default Music  
-BGM_ME_ZONE_06A_DEFAULT = Matrix 11 Post Saw QTE Area Default Music (???)  

/*MATRIX 11 - BOSS TACHY BGM*/  

-BGM_ME_BOSS_TACHY_INTRO = Matrix 11 Tachy Boss Fight Intro Music [Requires a Cue]  
-BGM_ME_BOSS_TACHY_INTRO_0717 = Matrix 11 Tachy Boss Fight Intro Music (Part 2???) [MAY Require a Cue]  
-BGM_ME_BOSS_TACHY_P1_INTRO = Matrix 11 Tachy Boss Fight Intro Music (???) [MAY Require a Cue]  
-BGM_ME_BOSS_TACHY_P1_LOOP = Matrix 11 Tachy Boss Fight Default Music Part 1 [Requires a Cue]  
-BGM_ME_BOSS_TACHY_P2 = Matrix 11 Tachy Boss Fight Default Music Part 2  [Requires a Cue]  


/*WASTELAND BGM*/  

-BGM_WASTELAND_UNDISCOVER_INTRO_100 = Wasteland Map General Music  
-BGM_WASTELAND_UNDISCOVER_LOOP_100 = Wasteland Map General Music  
-BGM_WASTELAND_UNDISCOVER_LOOP_100_B = Wasteland Map General Music (?)  
-BGM_WASTELAND_UNDISCOVER_LOOP_100_C = Wasteland Map General Music (?)  
-BGM_WASTELAND_UNDISCOVER_LOOP_P5 = Wasteland Map General Music Late Game (?)  

/*WASTELAND - SOLAR TOWER BGM*/  

-BGM_WASTELAND_ZONE02_SOLARTOWER = Wasteland Map Solar Tower Area Music  
-BGM_WASTELAND_ZONE02_SOLARTOWER_B = Wasteland Map Solar Tower Area Music (?)  
-BGM_WASTELAND_ZONE02_SOLARTOWER_BB = Wasteland Map Solar Tower Area Music (?)  
-BGM_WASTELAND_ZONE02_SOLARTOWER_C = Wasteland Map Solar Tower Area Music (?)  

/*WASTELAND - WEST/SOUTHWEST AREA BGM (??? AREA BENEATH DIGGER'S SITE)*/  

-NA_Stage_RuinsCity_Dynamic_LOOP = Wasteland Map DLC Music  
-NA_Stage_RuinsCity_Mid_LOOP = Wasteland Map DLC Music  

/*WASTELAND - MISC BGM*/  

-BGM_WASTELAND_DIGGER_INTRO = Wasteland Digger Intro Music [Requires a Cue with Concatenator Node]  
-BGM_WASTELAND_DIGGER_LOOP = Wasteland Digger Intro Music [Requires a Cue with Concatenator Node]  
-BGM_WASTELAND_BOSS_N3_130 = Wasteland Battle Music (Backtrack?) (With Tall Caped Robot)  
-BGM_WASTELAND_BOSS_N3_130R = Wasteland Battle Music (With Tall Caped Robot)  


/*XION BGM*/  

-BGM_E04_Xion_K_P1 = Xion Map General Music  
-BGM_E04_XION_K_P2 = Xion Map General Music  
-BGM_E04_XION_K_P3 = Xion Map General Music  
-BGM_E04_XION_K_P5 = Xion Map General Music  
-BGM_E04_XION_P5 = Xion General Music Late Game (?) (Actually I Dont Think This Is Late Game At All)  
-BGM_XION_EVENT_WINTER = Xion Map Seasonal Music  
-BGM_XION_SHOP_KAYA = Xion Kaya Shop Music  

/*XION - MISC BGM*/  

-BGM_XION_ACTOR_DancingCactus = Xion Cactus Seasonal Music  
-BGM_XION_ACTOR_ENYA_PIANO = Xion Enya General Music (Piano)  
-BGM_XION_ACTOR_ENYA_VOCAL_H = Xion Enya General Music (H Vocals)  
-BGM_XION_ACTOR_ENYA_VOCAL_L = Xion Enya General Music (L Vocals)  
-BGM_XION_ACTOR_ENYA_TRIO = Xion Enya Missions Completed Music (?) (Piano)  
-BGM_XION_ACTOR_ENYA_TRIO_VOCAL_H = Xion Enya Missions Completed Music (?) (H Vocals)  
-BGM_XION_ACTOR_ENYA_TRIO_VOCAL_L = Xion Enya Missions Completed Music (?) (L Vocals)  
-BGM_XION_ACTOR_ENYA_WINTER_INS = Xion Enya Seasonal Music (Piano)  
-BGM_XION_ACTOR_ENYA_WINTER_VOCAL = Xion Enya Seasonal Music (Vocals)  

/*------------------------------------------CHARACTERS--*/  
/*------------------------------------------CHARACTERS--*/  
/*------------------------------------------CHARACTERS--*/  

/*----------------------CHARA-EVE-VOICE--*/  
/*----------------------CHARA-EVE-VOICE--*/  

/*--CHAR-EVE-VOICE---ATTACK--*/ (This Section Is Really Messy, The Sounds Are Pretty Much All Shfufled Around These Actions)  

-vo_eve_atk_l1_VO = Large Sword Attack (Combo = L-L)  
-vo_eve_atk_l2_VO = Large Sword Attack/3rd Large Sword Attack (?) (Combo = L-L-L)  
-vo_eve_atk_l3_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_l4_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_l6_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_l8_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_l11_VO = Large Sword Attack  
-vo_eve_atk_l12_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_l14_VO = Large Sword Attack  
-vo_eve_atk_l15_VO = Large Sword Attack/2nd Large Sword Attack (?) (Combo = L-L)  
-vo_eve_atk_s1_VO = Small Sword Attack  
-vo_eve_atk_s2_VO = Small Sword Attack/Large Sword Attack  
-vo_eve_atk_s3_VO = Small Sword Attack  
-vo_eve_atk_s5_VO = Small Sword Attack  
-vo_eve_atk_s6_VO = Small Sword Attack  
-vo_eve_atk_s7_VO = Small Sword Attack/Large Sword Attack  
-vo_eve_atk_s8_VO = Small Sword Attack  
-vo_eve_atk_s9_VO = Small Sword Attack  
-vo_eve_atk_s10_VO = Large Sword Attack  
-vo_eve_atk_s11_VO = Land/Landing With Sword Unsheathed But Have Not Struck An Enemy (This Is So Dumb LOL)/Large Sword Attack  
-vo_eve_atk_s12_VO = Landing With Sword Unsheathed But Have Not Struck An Enemy (This Is So Dumb LOL)/Large Sword Attack/Small Sword Attack  
-vo_eve_atk_s13_VO = Land/Landing With Sword Unsheathed But Have Not Struck An Enemy (This Is So Dumb LOL)/Small Sword Attack  
-vo_eve_atk_s14_VO = Landing With Sword Unsheathed But Have Not Struck An Enemy (This Is So Dumb LOL)/Large Sword Attack/Small Sword Attack  
-vo_eve_atk_s15_VO = Small Sword Attack  
-vo_eve_atk_s16_VO = Small Sword Attack  
-vo_eve_atk_s17_VO = Small Sword Attack  
-vo_eve_atk_s18_VO = Small Sword Attack  
-vo_eve_cast_m1_VO = 3rd Large Sword Attack (?) (Combo = L-L-L)  
-vo_eve_cast_m2_VO = 3rd Large Sword Attack (?) (Combo = L-L-L)  
-vo_eve_cinematic_breath_01_VO = Land  
-vo_eve_cinematic_breath_02_VO = Land  
-vo_eve_cinematic_breath_03_VO = Land  
-vo_eve_social_breath_01_VO = Idle/Sitting On Bench Exhale  
-vo_eve_social_breath_02_VO = Idle/Sitting On Bench Exhale  
-vo_eve_social_breath_03_VO = Idle/Sitting On Bench Exhale  
-vo_eve_social_breath_04_VO = Idle/Sitting On Bench Exhale  

/*----------------------CHARA-EVE-SFX--*/  
/*----------------------CHARA-EVE-SFX--*/  

/*--CHARA-EVE-SFX---ATTACK-MELEE--*/  

-Hit_sword_nomarl_01 = Hit Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_sword_nomarl_02 = Hit Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_sword_nomarl_03 = Hit Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_sword_nomarl_04 = Hit Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_blunt_01 = Hit Flesh Enemy With Large Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_blunt_02 = Hit Flesh Enemy With Large Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_blunt_03 = Hit Flesh Enemy With Large Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_blunt_04 = Hit Flesh Enemy With Large Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_01 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_02 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_03 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_04 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_05 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_06 = Hit Flesh Enemy With Small Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_01 = Hit Flesh Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_02 = Hit Flesh Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_03 = Hit Flesh Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_04 = Hit Flesh Enemy With Small Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_06 = Hit Large/Stone Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_08 = Hit Large/Stone Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Blood_09 = Hit Large/Stone Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Hard_Blood01 = Hit Flesh Enemy With Small Attack (Quiet) (Plays With Hit_Monster_CRK_##) (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Hard_Blood02 = Hit Flesh Enemy With Small Attack (Quiet) (Plays With Hit_Monster_CRK_##) (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Hard_Blood03 = Hit Flesh Enemy With Small Attack (Quiet) (Plays With Hit_Monster_CRK_##) (Doesnt Affect Metal Enemies)  
-Hit_Monster_CRK_Sub_impact_01 = Hit Enemy With Blue Sparks-Creating Attack (?)  
-Hit_Monster_CRK_Sub_impact_02 = Hit Enemy With Blue Sparks-Creating Attack (?)  
-Hit_Sword_Defualt_07 = Hit Small (?) Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_Defualt_08 = Hit Small (?) Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_Defualt_09 = Hit Small (?) Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_Defualt_10 = Hit Small (?) Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-Hit_Sword_Defualt_11 = Hit Flesh Enemy With Large Sword Attack (Doesnt Affect Metal Enemies)  
-CPS_hit_Punch_01 = Kick/Punch Enemy (Beta X And Combos Involving Kicks Trigger This)  
-CPS_hit_Punch_02 = Kick/Punch Enemy (Beta X And Combos Involving Kicks Trigger This)  
-CPS_hit_Punch_03 = Kick/Punch Enemy (Beta X And Combos Involving Kicks Trigger This)  
-CPS_Hit_Critical_FX_1 = Hit Enemy With Blue Sparks-Creating Attack (?) (Can Play With CPS_Hit_critical_impact)  
-CPS_Hit_Critical_FX_2 = Hit Enemy With Blue Sparks-Creating Attack (?) (Can Play With CPS_Hit_critical_impact)  
-CPS_Hit_Critical_FX_3 = Hit Enemy With Blue Sparks-Creating Attack (?) (Can Play With CPS_Hit_critical_impact)  
-CPS_Hit_critical_impact = Hit Enemy With Blue Sparks-Creating Attack (?)  (Can Play With CPS_Hit_Critical_FX_#)  
-CPS_Monster_Bullet_02_1 = Parry/Reflect Enemy Projectile  
-CPS_Monster_Bullet_02_2 = Parry/Reflect Enemy Projectile  
-CPS_Monster_Bullet_02_3 = Parry/Reflect Enemy Projectile  
-Mon_slice_Small_1 = Kill Flesh Enemy With Sword (Unverified But Likely)  
-Mon_slice_Small_2 = Kill Flesh Enemy With Sword  
-Mon_slice_Small_3 = Kill Flesh Enemy With Sword  
-Mon_slice_Small_4 = Kill Flesh Enemy With Sword  

-Swing_sword_Mid_10 = 4th Small Sword Attack Swing (Combo = S-S-S-S) (Can Play During Other Moves)  
-Swing_sword_Short_06 = Small Sword Attack Swing (Plays In Random Order) (Can Play During Large Swings)  
-Swing_sword_Short_07 = Small Sword Attack Swing (Plays In Random Order) (Can Play During Large Swings) (Always Plays For Rush Attack Secondary Attack)  
-Swing_sword_Short_08 = Small Sword Attack Swing (Plays In Random Order) (Can Play During Large Swings)  
-Swing_sword_Short_09 = Small Sword Attack Swing (Plays In Random Order) (Can Play During Large Swings)  
-PC_Skill_Air_GuardBreak_S = Aerial Triangle Dive (From Even Ground Jump Height?)  
-PC_Skill_ChainStab_Impact3_2 = Beta Attack (Square) Poke Final (Without Using Jumping Stab)  
-PC_Skill_ChargePoint_1 = Beta Attack (Triangle) (First Stab???)  
-PC_Skill_ChargePoint_2 = Beta Attack (Triangle) Extra Attack Wind Up  
-PC_Skill_ChargeStart = Beta Attack (Triangle) Wind Up  
-PC_Skill_ChargeSlash = Beta Attack (Square) Extra Attack Swing End  
-PC_Skill_ChargeWhoosh_1 = Beta Attack (Triangle) Attack Swing  
-PC_Skill_ChargeWhoosh_2 = Beta Attack (Triangle) Attack Swing  
-PC_Skill_dashAttack_whoosh = Rush Attack Travel  
-PC_Skill_dashAttack_whoosh_2 = Rush Attack Travel  
-PC_Skill_FlashBehindAttack_E = Blink Reappear  
-PC_Skill_FlashBehindAttack_E_2 = Blink Sword Attack Swing  
-PC_Skill_FlashBehindAttack_S = Blink Starting Sidestep   
-PC_Skill_Fusion_Swrod_M_2 = Small Sword Attack Swing (Combo = L-S-S)  
-PC_Skill_Air_GuardBreak_fall = Kick Attack Swing (?) (Combo = L-S-L)  
-PC_Skill_JustEvade3 = Perfect Dodge (Loud)  
-PC_Skill_JustEvade_StrongAttackCombo_N_1 = Blink Sword Attack  
-PC_Skill_JustParry_LightAttack_2 = 3rd Small Sword Attack Swing (Combo = S-L-S)  
-PC_Skill_StrongAttack5_sword = 2nd (?) Large Sword Attack Swing (L-L-L)  
-PC_Skill_Sword_Normal_LightAttack8_Whoosh = Small Sword Attack Swing (Combo = L-S-S) (High Pitch)  
-PC_Skill_Sword_Normal_StrongAttack3_Whoosh = Kick Attack Start (Combo = L-S-L)  
-PC_Skill_Whoosh_Sharp_M = Large Sword Swing Ending (Combo = L-L)  
-PC_Skill_Whoosh_Sharp_M_Cine = Small Sword Attack Swing (Combo = L-S-S), 2nd Small Sword Attack Swing (Combo = L-S-L-S)  
-PC_Skill_Whoosh_Sharp_S = Small Sword Attack Swing (Combo = L-S)  
-PC_Skill_Whoosh_Sharp_S2 = Rush Attack Swing End  
-Proto_Sword_Strongattack_01 = 1st Large Sword Attack Swing (Always Plays)  
-Proto_Whoosh_Skills_01 = Large Sword Attack Swing (Combo = L-L) (Loud)  
-Proto_WhooshSword_Mid_02 = Large Sword Attack Swing (Combo = S-L)  
-Proto_WhooshSword_Mid_04 = Sword Position Reset Swing (When Eve Swings Her Sword Back To Her Side After An Attack Is Finished)  
-P_Eve_Sword_Normal_MoveBackAttack1_E_02 = 4th Attack Wind Up (Combo = S-L-L-L)  
-Sword_Finish_Attack_2 = 3rd Large Sword Attack Swing (Combo = L-L-L) (Loud)  
-EVE_magic_spark_explo_03 = 4th Large Sword Attack Swing (Combo = S-L-L-L)  
-EVE_magic_spark_explo_04 = 4th Large Sword Attack Swing (Combo = S-L-L-L)  
-EVE_magic_spark_explo_05 = 4th Large Sword Attack Swing (Combo = S-L-L-L)  
-EVE_Skill_start_03 = Rush Attack Travel  
-SE_Sword_Whoosh_01 = 2nd Large Sword Attack Swing (Combo = S-L-L)  
-EVE_SE_Shing01 = 3rd Large Sword Attack Wind Up (Combo = S-L-L-L)  
-UI_BetaActive = Beta Attack Electricty/FX (?) (Noticed On Default Triangle And X Beta Attacks) (Might Be A UI Popup Based On The Name)  
-PC_whoosh_BigMotion_2 = Beta Attack (Default?) Triangle Finishing Swing  
-Impact_Rock_Small_01 = Sword Attack Hitting Rock  
-Impact_Rock_Small_02 = Sword Attack Hitting Rock  
-Cable_Spark2_1 = Sword Attack Creating Sparks On Ground  
-Cable_Spark2_2 = Sword Attack Creating Sparks On Ground  
-Cable_Spark2_3 = Sword Attack Creating Sparks On Ground  
-swish_spark_01 = Beta (Square) 2nd Poke (? Might Just Be The Sparks That Shoot From It)  

/*--CHARA-EVE-SFX---ATTACK-PROJECTILE--*/  

-Drone_Gun_Heavy_E = Stop Aiming Gun  
-Drone_Gun_Heavy_S = Aimed Gun Slug (?)  
-Drone_Gun_Heavy_Change = Aimed Gun Slug (?)  
-Drone_Gun_Missile_Change = Start Targeting Gun Stinger (Does Not Always Play)  
-Drone_Gun_RailGun_Change = Start Charging Gun Laser  
-P_Eve_Gun_LockOn_2 = Gun Stinger 2 Locks On A Single Target  
-P_Eve_Gun_LockOn_3 = Gun Stinger 3 Locks On A Single Target   
-P_Eve_Gun_LockOn_4 = Gun Stinger 4 Locks On A Single Target  
-P_Eve_Gun_LockOn_5 = Gun Stinger 5 Locks On A Single Target  
-P_Eve_Gun_LockOn_6 = Gun Stinger 6 Locks On A Single Target  
-P_Eve_Gun_LockOn_7 = Gun Stinger 7 Locks On A Single Target  
-P_Eve_Gun_LockOn_8 = Gun Stinger 8 Locks On A Single Target  
-P_Eve_Gun_ShootMissile1_Cancel_1 = Cancelled Targeting With Stinger  
-P_Eve_Gun_ShootMissile1_Cancel_2 = Cancelled Targeting With Stinger  
-P_Eve_Gun_ShootMissile1_Cancel_3 = Cancelled Targeting With Stinger  
-Drone_Gun_ShootRailgun1_L1 = Laser Charge Up Start  
-Drone_Gun_ShootRailgun1_L4 = Laser Charge Up Complete  
-Drone_Gun_ShootRailgun1_Cancel = Laser Charge Early/Overheat Cancel (When You Hold The Charge Too Long Or Didnt Let It Charge All The Way)  
-P_Eve_Gun_ShootRailgun1_E_Layer01 = Laser Shot Concluded (Louder)  
-P_Eve_Gun_ShootRailgun1_E = Laser Shot Concluded (Quieter)  
-Drone_Gun_ShootRailgun1_S1 = Laser Fired  
-PC_Skill_Gun_Shoot_Slug_1 = Gun Slug Gunshot (Louder)  
-PC_Skill_Gun_Shoot_Slug_2 = Gun Slug Gunshot (Louder)  
-PC_Skill_Gun_Shoot_Slug_3 = Gun Slug Gunshot (Louder)  
-PC_Skill_Gun_Shoot_Slug_4 = Gun Slug Gunshot (Louder)  
-PC_Skill_Gun_Tail_Bright_1 = Gunshot Echo  
-PC_Skill_Gun_Tail_Bright_2 = Gunshot Echo  
-PC_Skill_Gun_Tail_Bright_3 = Gunshot Echo  
-PC_Skill_Gun_Tail_Bright_4 = Gunshot Echo  
-PC_Skill_Gun_Tail_Dark_1 = Gunshot Echo  
-PC_Skill_Gun_Tail_Dark_2 = Gunshot Echo  
-PC_Skill_Gun_Tail_Dark_3 = Gunshot Echo  
-PC_Skill_Gun_Tail_Dark_4 = Gunshot Echo  
-PC_Skill_SmartMissile_Bullet_1 = Gun Stinger Impact  
-PC_Skill_SmartMissile_Bullet_2 = Gun Stinger Impact  
-PC_Skill_SmartMissile_Bullet_3 = Gun Stinger Impact  
-PC_Skill_SmartMissile_Bullet_4 = Gun Stinger Impact  
-PC_Skill_SmartMissile_Shot_1 = Gun Stinger Fired  
-PC_Skill_SmartMissile_Shot_2 = Gun Stinger Fired  
-PC_Skill_SmartMissile_Shot_3 = Gun Stinger Fired  
-sfx_gun_noammo_01 = No Ammo Click  
-sfx_gun_noammo_02 = No Ammo Click  
-sfx_gun_noammo_03 = No Ammo Click  
-sfx_gun_noammo_04 = No Ammo Click  

/*--CHARA-EVE-SFX---SPECIAL--*/  

-sfx_battle_WeakPoint_normal_new = Enemy WeakPoint Exposed  
-sfx_battle_signal_Blink2 = Enemy Blink Attack Flash  
-sfx_battle_signal_Repulse2 = Enemy Repulse Attack Flash  
-sfx_battle_repulseAlert = Eve Repulse Opportunity Flash  
-sfx_battle_behindAlert = Eve Blink Opportunity Flash  
-SE_PC_AddDamageImpact1 = Retribution SFX 1 (Plays When Throwing Enemy Onto Their Back)  
-EVE_SE_LinkSignal = Perfect Dodge Secondary SFX, Retribution SFX 2 (There Are More SFX Played Alongside This)  

/*--CHARA-EVE-SFX---GUARD--*/  

-EVE_PC_Normal_Parry_Sword_01 = Blocked Attack (Very Low Pitch)  
-EVE_PC_Normal_Parry_Sword_03 = Blocked Attack (Very Low Pitch)  
-EVE_PC_Normal_Parry_Sword_04 = Blocked Attack (Very Low Pitch)  
-EVE_SE_SwishSofft = Guard Up (Always Plays)  
-EVE_SE_Swishsoft1 = Guard Up  
-Hit_Monster_CRK_Layer01 = Enemy Hit Eve Guard (Plays With Hit_Monster_CRK_Sub) (Low Pitch, Low Tempo)  
-Hit_Monster_CRK_Sub = Enemy Hit Eve Guard (Plays With Hit_Monster_CRK_Layer01)  
-PC_Guard_Mid_1 = General, Even Ground Blocked Attack  
-PC_Guard_Mid_2 = General, Even Ground Blocked Attack  
-PC_Guard_Mid_3 = General, Even Ground Blocked Attack  
-PC_parry = Blocked Attack (Guard Was Held Up Slightly Beforehand)  
-Proto_Parry = Blocked Attack (Guard Was Held Up Moderately Beforehand)  
-Proto_Parry_Impact = Blocked Attack (From A Straight Jab Attack ???)  
-PC_just_parry_3 = Parry (Plays With PC_just_parry_Main_5_fx_1)  
-PC_just_parry_Main_5_2 = Parry Secondary SFX (Plays With PC_just_parry_Main_5_fx_1)  
-PC_just_parry_Main_5_fx_1 = Parry FX (Plays With PC_just_parry_3)  
-SE_AddHitImpact_Low1 = (???) Perfect Dodge 1 (???)  

/*--CHARA-EVE-SFX---CLOTHING/MOVEMENT--*/  

-PC_SE_ExtraSprint_Begin = Speed-Boosted Dash Start  
-PC_SE_ExtraSprint_Loop = Speed-Boosted Dash Loop  
-PC_FoldSword_Open = Unsheath Sword  
-PC_foley_whoosh1_1 = Airborne While Mantling Up or Down, Leaping Up Ladders, or Roll Climbing Ledges  
-PC_Foley_Jump_whoosh_D_1 = Regular Jump  
-PC_Foley_Jump_whoosh_D_2 = Regular Jump  
-PC_Foley_Jump_whoosh_D_3 = Regular Jump (?)/Airborne While Jumping or Roll Climbing Ledges  
-SE_Cloth_whoosh_03 = Climbing Up Cliff/Ledge Regular (?)  
-PC_Evade_Water_M_1 = Regular Dash In Puddle  
-PC_Evade_Water_M_2 = Regular Dash In Puddle  
-PC_Evade_Water_M_3 = Regular Dash In Puddle  
-PC_foley_whoosh1_3 = Climbing Cliff/Ledge Quick Spin  
-PC_foley_whoosh1_4 = Climbing Cliff/Ledge Quick Spin  
-SE_Move_Air_Whoosh_02 = Air Dash Woosh  
-SE_Move_Air_Whoosh_03 = Air Dash Woosh  
-Move_Evade_Whoosh_01 = 2nd Back Dash Of Double Back Dash/Air Dash Secondary SFX  
-Move_Evade_Whoosh_02 = (??? Havent Come Across It)  
-Move_Evade_Whoosh_03 = 2nd Back Dash Of Double Back Dash/Air Dash Secondary SFX  
-PC_Evade_Jump_1 = Air Dash  
-PC_Evade_Jump_2 = Air Dash  
-PC_Evade_Jump_3 = Air Dash  
-PC_Evade_M_1 = Air Dash Secondary SFX/Double Backdash Secondary SFX/Perfect Dodge Secondary SFX  
-PC_Evade_M_2 = Air Dash Secondary SFX/Double Backdash Secondary SFX/Perfect Dodge Secondary SFX  
-PC_Evade_M_3 = Air Dash Secondary SFX/Perfect Dodge Secondary SFX (Low-ish)  
-PC_Evade_S_1 = Regular Dash  
-PC_Evade_S_2 = Regular Dash  
-PC_Evade_S_3 = Regular Dash  
-EVE_Movement_Cloth_02 = Clothes Rustle (During Large Attack, Combo = L-L)  
-EVE_bodyfall_common_01 = Beta Attack (Default?) X Landing  
-EVE_bodyfall_common_02 = Beta Attack (Default?) X Landing  
-EVE_bodyfall_common_03 = Beta Attack (Default?) X Landing  
-EVE_Swim_MoveSound = Wading in Water  
-EVE_UWSwim_MoveSound = Swimming Stopped  
-EVE_UWSwim_MoveSound_Idle =  Wading in Water  
-EVE_Swim_Phase1 = Wading In Water, Swimming Through Water (Wading Is Quiet, Swimming Is Loud)  
-EVE_Swim_Phase2 = Wading In Water, Swimming Through Water (Wading Is Quiet, Swimming Is Loud)  
-EVE_Swim_Phase3 = Wading In Water, Swimming Through Water (Wading Is Quiet, Swimming Is Loud)  
-EVE_Swim_Phase5 = Wading In Water, Swimming Through Water (Wading Is Quiet, Swimming Is Loud)  
-EVE_Swim_Phase6 = Wading In Water, Swimming Through Water (Wading Is Quiet, Swimming Is Loud)  
-EVE_UWSwim_Phase1 = Wading UnderWater, Swimming UnderWater (Wading Is Quiet, Swimming Is Loud)  
-EVE_UWSwim_Phase2 = Wading UnderWater, Swimming UnderWater (Wading Is Quiet, Swimming Is Loud)  
-EVE_UWSwim_Phase3 = Wading UnderWater, Swimming UnderWater (Wading Is Quiet, Swimming Is Loud)  
-EVE_UWSwim_Phase4 = Wading UnderWater, Swimming UnderWater (Wading Is Quiet, Swimming Is Loud)  
-EVE_Swim_Out_01 = Exiting Water  
-EVE_Swim_Out_02 = Exiting Water  
-EVE_SE_JumpStep_Water1 = Falling Into Water  
-PC_SE_CampChair_Start = Sit In Camp Chair  
-PC_SE_CampChair_End = Stand Up From Camp Chair/Shuffle Around In Chair  
-EVE_SE_ClothMid = Cloth Movement (Plays When: Standing Posture Shifts, Landing From Air Dash, One Arm Ledge Climb, Sitting Down, Moving While Seated, Getting Up From Seat, Interacting With Skill Machine, etc)  
-EVE_SE_ClothShort = Cloth Movement (Plays When: Abrupt Forward Direction Change, Dashing Forward From Idle/Walking State, Idle Pose Kick, Landing From Jump, Starting Run, etc)  

/*--CHARA-EVE-SFX---MISC--*/  

-EVE_CampRest = Rest Recharge  
-EVE_CampRest_2 = ???  
-EVE_SE_AmpleToss = Potion/Coin (?) Toss  
-PC_Basic_UsePotion_1 = Healing Potion Used Mist  
-PC_Basic_UsePotion_2 = Healing Potion Used Mist  
-PC_Basic_UsePotion_3 = Healing Potion Used Mist  

/*--------------------------------------------ENEMY--*/  
/*--------------------------------------------ENEMY--*/  
/*--------------------------------------------ENEMY--*/  

/*--ENEMY-SFX---MISC--*/  

-EVE_MON_DespawnVaporize3 = Enemy Despawn (Noticed In Training Room)  

/*------------------------------------------OBJECTS--*/  
/*------------------------------------------OBJECTS--*/  
/*------------------------------------------OBJECTS--*/  

/*--OBJECTS-SFX---CAN--*/  

-PC_SE_Item_CanShowing_brass_1 = Can Shown To Screen Fanfare  
-PC_SE_Item_CanShowing_brass_2 = Can Shown To Screen Fanfare  
-PC_SE_Item_CanShowing_grab_1 = Can Collected Pickup, Put Away SFX  
-PC_SE_Item_CanShowing_grab_2 = Can Collected Pickup, Put Away SFX  
-PC_SE_Item_CanShowing_grab_3 = Can Collected Pickup, Put Away SFX  

/*---------------------------------------------NPC--*/  
/*---------------------------------------------NPC--*/  
/*---------------------------------------------NPC--*/  

/*--NPC-ADAM-DRONE-SFX---MOVEMENT/SCAN--*/  

-Drone_motion_arrive3_2 = Drone Stopping Travel And Lowering  
-Drone_motion_arrive3_1 = Drone Stopping Travel And Lowering  
-Drone_date_scan_short_4 = Drone Scanning Twirl  
-Drone_date_scan_short_3 = Drone Scanning Twirl  
-Drone_date_scan_short_2 = Drone Scanning Twirl  
-Drone_date_scan_short_1 = Drone Scanning Twirl  
-Drone_date_scan_loop = Drone Scanning Surface With Lasers Loop  
-N_Drone_Scan_FX_Pad = Player Pressed Scan Button (?)  
-N_Drone_Scan_start_Full_2 = Player Pressed Scan Button  
-N_Drone_Scan_start_Full = ???  
-N_Drone_Scan_start = Drone Scan Form Activated  
-N_Drone_Scan_impact = Drone Scan Pulse Sent Out (Drone Body Opens)  
-N_Drone_Scan_FX = Drone Scan Pulse Sent Out (???)  
-N_Drone_Scan_FX_2 = Drone Scan Pulse Sent Out (???)  
-N_Drone_Scan_FX_3 = Drone Scan Pulse Sent Out  
-N_Drone_Scan_Close = Drone Scan Detect Object/Pulse Sent Out (???)  
-N_Drone_Scan_Tail = Drone Scan Detect Object (Repeats)  
-N_Drone_UW_Scan_FX = Player Pressed Scan Button Underwater  
-N_Drone_UW_Scan_start_1 = Player Pressed Scan Button Underwater  
-N_Drone_UW_Scan_Close = (?) (Always Plays Shortly After N_Drone_UW_Scan_FX & N_Drone_UW_Scan_start_1)  


/*--------------------------------------------------UI--*/  
/*--------------------------------------------------UI--*/  
/*--------------------------------------------------UI--*/  

/*--UI-SFX--*/  

-EVE_UI_DoorOpenSignal = Open Door That Was Just Unlocked (Tested On Rusty Little Gate)  
-EVE_UI_GEAR_CLEAR = Main Menu Up/Down Navigation  
-EVE_UI_GEAR_MOUNT = Main Menu Enter Sub Menu, Exit Game  
-EVE_UI_ItemGet = Pickup Collected (?)  
-EVE_UI_ItemGet02 = Advanced Nano Collected/Pickup Collected (?)  
-EVE_UI_ItemGet03 = Gold Collected (?)/Pickup Collected (?)  
-EVE_UI_ItemGet04 = Vitcoin Collected/Pickup Collected (?)  
-EVE_UI_ItemGet05 = Advanced Polymer Material Collected/Pickup Collected (?)  
-EVE_UI_Minigame_GameFailed = Locked Treasure Chest Keypad Popup  
-ui_beep = Training Room Input Log Popup (?)  
-UI_Common_Cancel = Back Out Of UI Slider  
-UI_Common_Cancel_2 = Back Out Of UI Slider  
-UI_Common_Popup_Close = Back Out Of Main Menus Sub Menus/Back Out Of Training Room/Back Out Of Potion Machine, Upgrade Machine, And Phone Booth  
-UI_Common_Popup_Confirm = Open "View & Set Controls" Diagram/ "Open Quit" Game Box  
-ui_button = Back Out Of Main Menus Sub Menus/Back Out Of Training Room/Back Out Of Potion Machine, Upgrade Machine, And Phone Booth  
-UI_Corpse = Pickpocketed Corpse (For Note?)  
-UI_Done_4 = Pressed X For "Press X" Prompt (Getting Up From Seat, Confirming Quit Game, Confirming Body Core Collection)  
-UI_Guide_Open_2 = Combat Instructions/Info Popup  
-UI_MainHUD_Skill_BetaCharge = Beta Meter Charged/Triangle Lunge Meter Charged  
-UI_MainHUD_Start = Body Core Obtained Popup (Another Sounds Plays Slightly After This Starts)  
-UI_Minigame_Arrow_Correct = Corspe Note Popup (? 'Minigame' For A Dead Body Is Crazy)  
-UI_move_in_verb = Entering Sub-Menu  
-UI_move_out_verb = Main Menu Exiting Sub-Menu  
-EVE_UI_Minigame_Cancel = Main Menu Back Out, Game Unpause  
-EVE_UI_Minigame_GenerateRandomCode = Main Menu Back Out, Game Unpause  
-UI_Tab_H_03 = Main Menu Vertical Move (Originally Said Horizontal, May Have Been A Typo)  
-EVE_UI_MENU_OPEN = Game Pause, Enter Skill Tree  
-UI_Interaction_Success_MainHUD = Interact With R2 Prompts (Camp Chair, Vending Machine, Record Player, Skill Machine)  
-UI_Manual_Detail = Up/Down Record Player Navigation  
-ui_notice = Chair Heal Text Popups  
-UI_QTE_Enem_FadeIn = QTE Opportunity Prompt (Retribution Chain Attack, Ambush)  
-UI_QTE_success = Opportunity Accepted (Retribution Chain Attack, Ambush)  
-UI_Setting_Select = Enter UI Dropdown or Slider  
-UI_SkillExp_Count_Start = SP Gain (Or Rather, Gain Stop SFX)  
-UI_SkillExp_Count_3 = SP Gain  
-UI_SkillPoint_Update = SP Level Up  
-UI_SkillPoint_Update_C = SP Level Up  
-UI_SkillTree_Open = Enter Skill Tree From World + From Training Room  
-UI_SkillTree_ChangeSkillList01 = Left/Right Skill Tree Category Switch   
-UI_SkillTree_GroupFocus = Enter Training Room  
-UI_Tab_1 = (Pause?) Menu L1/R1 Tab Switch  
-UI_Tab_2_4 = Up/Down + Left/Right Settings Menu Navigation/Skill Tree Token Navigation/Enter Potion Machine/Enter Phone Booth  
-UI_Teleport_Done = Enter Training Room  
-UI_Title_Menu_Confirm = Enter A Main Menu Option (Pressing X On Any Listed Section)  
-UI_Title_Menu_Confirm_2 = Enter A Main Menu Option (Pressing X On Any Listed Section)  
-UI_Title_Menu_Confirm_3 = Enter A Main Menu Option (Pressing X On Any Listed Section)  
-UI_TurnTable_Close = Back Out Of Record Player  
-UI_TurnTable_ListMove = Up/Down Record Player Navigation   
-UI_TurnTable_Open = Enter Record Player  
-UI_TurnTable_Play = Play Record Player Song  
-UI_GoldUpcount_2_R = Picked Up Gold  
-ui_done_2 = Back Out Of Yes/No Prompt (Noticed When Exiting The Game, May Be Just For Exiting)  
-UI_Corpse_Popup = Enter Yes/No Prompt (Noticed When Exiting The Game, May Be Just For Exiting)  
-UI_volumecontroller_4 = Left/Right UI Slider Navigation  
-UI_volumecontroller_5 =  Left/Right UI Slider Navigation  
-UI_whoosh_back = Back Out Of Locked Treasure Chest Keypad Popup  
-UI_Workshop_Open = Enter Upgrade Machine  




/*--------------------------------------------------BOSS-CODENAME-LIST--*/  
/*--------------------------------------------------BOSS-CODENAME-LIST--*/  
/*--------------------------------------------------BOSS-CODENAME-LIST--*/  

Opener - Abaddon  
GrubShooter - Corrupter  
Gorilla - Gigas  
HedgeBoarBrute - Brute  
GorillaBrokenHead - Gigas in Wasteland  
Sawshark - Stalker  
SkullJuggernaut - Juggernaut  
Tachy - Tachy  
SawsharkWasteland - Stalker in Great desert  
OpenerWasteland - Abaddon in Great desert  
Behemoth - Behemoth  
WeaponMaster - Belial  
Marionette - Karakuri  
Crawler - Democrowler  
Golgon - Demogolgon  
RavenBeast - Unindentified Naytiba  
Raven - Raven  
ExoSuit - Providence  
Elder - Elder Naytiba  
Mann - Mann  
Scarlet - Scarlet  

-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------DONT WORRY ABOUT ANYTHING BELOW HERE------------------------------------  
------------------------------SCROLL BACK UP-----------------------------------------------  
----------------------------- -MANAGEMENT -------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  
-------------------------------------------------------------------------------------------  

-----CPS_Monster_CRK_Blood_Cue = Hit Enemy With Sword (Blood Drawn?)  
-----CPS_Monster_CRK_Hard_Cue = Hit Enemy With Sword (Blood Drawn?)  
-----CPS_Monster_Machine_Cue = Hit Metal Enemy With Small Sword Attack  
-----CPS_Monster_Machine_Heavy_Cue = Hit Metal Enemy With Large Sword Attack  
-----Swing_sword_Short_01_Cue = 1st Small Sword Attack Swing (Always Plays)  
-----Swing_sword_Mid_01_Cue = 4th Small Sword Attack Swing (Combo = S-S-S-S)/1st Large Sword Attack Swing (Always Plays)  
-----Proto_WhooshSword_Mid_04_Cue = Sword Position Reset Swing (When Eve Swings Her Sword Back To Her Side After An Attack Is Finished)  
-----PC_whoosh_BigMotion_3_Cue = Beta Attack (Quadruplet) Final Lunge (Combo = L1+Square-L1+Square)  
-----EVE_PC_SwordMechanismClose_Cue = Sheath Sword  
-----EVE_PC_SwordMechanismOpen_Cue = Unsheath Sword  
-----PC_Foley_Jump_whoosh_D_Cue = Regular Jump (Always Plays)  
-----PC_HurdleUp_L_Cue = Large Hurdle  
-----PC_HurdleUp_M_Cue = Medium Hurdle  
-----PC_Foley_Jump_whoosh_S_Cue = Climb Quick Spin  
-----PC_Foley_Jump_whoosh2_Cue = Jump While In Water  
-----PC_Cloth_Hard_L_Cue = Jump While In Water  
-----Move_Evade_Whoosh_01_Cue = Air Dash (Always Plays)  
-----PC_Evade_S_Cue = Regular Dash  
-----SE_Cloth_whoosh_01_Cue = Perfect Dodge  
-----PC_Evade_M_Cue = Perfect Dodge/Air Dodge  
-----EVE_Swim_Out_02_Cue = Walking Through Water (Knee-Waist Height)  
-----PC_Cloth_M_Cue = Cloth Movement (Plays When: Idle Pose Yawn-Stretch, Idle Pose Look Around, etc)  
-----PC_hand_touch_concrete_Cue = Run Into Concrete (???) Quick Spin On Ground Level Concrete (???)  
-----PC_Foley_Grab_Cue = Catch Heal Potion After Initial Flick  
-----PC_HurdleUp_M_Cue = Climbing Medium Height Ledge (She Boosts Herself Up With Both Hands)  
-----Obj_Box_Pannel_Open_Cue = Passcode Treasure Box Screen Popout  
-----Obj_Turntable_Switch_Cue = Supply Camp Activation  
-----N_Drone_Scan_FX_pad_Cue = Player Pressed Scan Button  
-----N_Drone_Scan_start_Cue = Drone Scan Form Activated  
-----N_Drone_Scan_Close_Cue = Drone Scan Form Retracted  
-----N_Drone_Scan_impact_Cue = Drone Scan Detect Object  
-----NPC_DeadBody_Fall_1_Cue = Dead Corpse Fall Over After PickPocketing Them  
-----NPC_DeadBody_Fall_Cloth_Cue = Dead Corpse Fall Over After PickPocketing Them  

/*--------------------------------------------------TESTED--*/  
/*--------------------------------------------------TESTED--*/  
/*--------------------------------------------------TESTED--*/  
-Sound/Character/Cloth_new  
-Sound/Character/Footsteps  
-Sound/Character/Hit  
-Sound/Character/NPC  
-Sound/Character/SE  
-Sound/Character/Skill  
-Sound/Cinema  
-Sound/Dev  
-Sound/Effect  
-Sound/LevelSeq  
-Sound/MON (Too Much Going On)  
-Sound/Motion  
-Sound/Niagra  
-Sound/Object  
-Sound/World/BGM  
-Sound/World/PhysicObjs  
