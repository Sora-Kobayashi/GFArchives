
# ZoneServer all commands
`"/ban <ch_id> <minute> <reason>: ban character"`.  
`"ban <number> <number> <word>"`.  
`"bc <number> <number> <rest_input>"`.  
***
`"/ban <ch_name> <minute> <reason>: ban character"`.  
`"bcn <word> <number> <rest_input>"`.  
***
`"reload_itemmall_db : reload itemmall db"`.  
`"reload_itemmall_db"`.  
***
`"/announce <message> : announce something"`.  
`"announce <rest_input>"`.  
`"gm <rest_input>"`.  
***
`"/channel_limit <id> <minute>: channel usage limitation"`.  
`"channel_limit <number> <number>"`.  
`"cl <number> <number>"`.  
***
`"/channel_limit_name <charname> <minute>: channel usage limitation"`.  
`"channel_limit_name <word> <number>"`.  
`"cln <word> <number>"`.  
***
`"set_node_exp : set node exp rate"`.  
`"set_node_exp <number> <number>"`.  
`"sne <number> <number>"`.  
***
`"set_node_gold : set node gold rate"`.  
`"set_node_gold <number> <number>"`.  
`"sng <number> <number>"`.  
***
`"set_node_drop : set node drop rate"`.  
`"set_node_drop <number> <number>"`.  
`"snd <number> <number>"`.  
***
`"/set_node_np : set node np rate"`.  
`"set_node_np <number> <number>"`.  
`"snn <number> <number>"`.  
***
`"/transport_char_revive_point <char_id> : transport character to revive point"`.  
`"transport_char_revive_point <number>"`.  
`"tcrp <number>"`.  
***
`"/transport_char_revive_point_name <char_name> : transport character to revive point by name"`.  
`"transport_char_revive_point_name <word>"`.  
`"tcrpn <word>"`.  
***
`"/transport_char_point <char_id> <node_id> <x> <y> : transport character to point"`.  
`"transport_char_revive_point <number> <number> <number> <number>"`.  
`"tcrp <number> <number> <number> <number>"`.  
***
`"/transport_char_revive_point_name <char_name> <node_id> <x> <y> : transport character to point by name"`.  
`"transport_char_revive_point_name <word> <number> <number> <number>"`.  
`"tcrpn <word> <number> <number> <number>"`.  
***
`"/return item <receiver_id> <log> : use mail return an item to player from log"`.  
`"return_item <number> <rest_input>"`.  
`"ri <number> <rest_input>"`.  
***
`"/return gold <receiver_id> <gold>: use mail return gold to player"`.  
`"return_gold <number> <word>"`.  
`"rg <number> <word>"`.  
***
`"/send_sys_mall_queue <receiver_id> : send system mall from sys_mail_queue"`.  
`"send_sys_mail_queue <number>"`.  
`"ssmq <number>"`.  
***
`"/account_ban <account_name> <char_id> <minute> <reason> : ban char by account"`.  
`"account_ban <word> <number> <number> <rest_input>"`.  
`"ab <word> <number> <number> <rest_input>"`.  
***
`"/sys_delete_mail <char_id> <mail_id> : system delete char all mail"`.  
`"sys_delete_mail <number> <number>"`.  
`"sdm <number> <number>"`.  
***
`"/ban <ch_id> <minute> <reason>: ban character"`.  
`"ban <number> <number> <word>"`.  
***
`"/tpa_save <ch_id>: tpa character to save point"`.  
`"tpa_save <number>"`.  
***
`"/no_speak <ch_id> <minute> <reason>: character no speak"`.  
`"no_speak <number> <number> <word>"`.  
***
`"/gmannounce <msg>: GM Announce"`.  
`"gmannounce <word>"`.  
***
`"/offline_ctrl <ctrl_type> <ch_name> <minute> <reason>: offline ctrl"`.  
`"offline_ctrl <word> <word> <number> <word>"`.  
***
`"/get_player_info <ch_name>: get_player_info"`.  
`"get_player_info <word>"`.  
***
`"/delete_item <ch_id> <ch_name> <con_type> <item_id>: delete_item"`.  
`"delete_item <number> <word> <word> <number>"`.  
***
`"/add_item <sender> <title> <content> <ch_id> <ch_name> <item_id> <com_id> <dur> <em1> <em2> <em3> <em4> <em5> <em6> <str> <ec1> <ec2> <ec3> <ec4> <ec5> <ec6> <c_type>: add_item"`.  
`"add_item <word> <word> <word> <number> <word> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number> <number>"`.  
***
`"/server_data_test <type> <item_id> <amount>: get_server_data_test"`.  
`"server_data_test <word> <number> <number>"`.  
***
`"/get_player_locate <player_id>: get player locate"`.  
`"get_player_locate <number>"`.  
***
`"/setPMS <player_id> <mmission_id> <pms_id> <state>: set PMS"`.  
`"setPMS <number> <number> <number> <number>"`.  
***
`"/set_money <player_id> <money>: set Money"`.  
`"set_money <number> <word>"`.  
***
`"/modify_mail <player_id> <mail_id> <modify_type>: Modify Mail"`.  
`"modify_mail <number> <number> <number>"`.  
***
`"/shut_down: shut down"`.  
`"shut_down"`.  
***
`"/kick_out <player_ip> <node_id> : kick out player"`.  
`"kick_out <number> <number>"`.  
***
`"/exchange items <char id> <node_id> <pin> <size> <item_id> <item_number> ... "`.  
`"exchange items <number> <number> <word> <number> <rest_input>"`.  
***
`"/family_set_emblem_fail <char id> <node_id>"`.  
`"family_set_emblem_fail <number> <number>"`.  
***
`"/trace_result <receiver_id> <target_id> <node_id>"`.  
`"trace_result <number> <number> <number>"`.  
***
`"/do_aw_put_treasure <receiver_id> <item_id> <node_id> <amount> <x> <y>"`.  
`"do_aw_put_treasure <number> <number> <number> <number> <number> <number>"`.  
***
`"/update_prestige <ch_id> <node_id> <prestige_id> <level> <exp>"`.  
`"update_prestige <number> <number> <number> <number> <number>"`.  
***
`"/captcha_punish <ch_id> <punish_type> <duration>"`.  
`"captcha_punish <number> <number> <number>"`.  
***
`"/update_health <ch_id> <online_time> <offline_time>"`.  
`"update_health <number> <number> <number>"`.  
***
`"/health <ch_id> <health_rule> <online_time> <offline_time>"`.  
`"health <number> <number> <number> <number>"`.  
***
`"/gm_tool_login_result <account> <account_id> <privilege>"`.  
`"gm_tool_login_result <word> <number> <number>"`.  
***
`"/gm_tool_ban_result <ch_name> <gm_name> <result>"`.  
`"gm_tool_ban_result <word> <word> <number>"`.  
***
`"/get_net_cafe_vip <ch_id> <type>"`.  
`"get_net_cafe_vip <number> <number>"`.  
***
`"/net_cafe_vip_over <ch_id>"`.  
`"net_cafe_vip_over <number>"`.  
***
`"/update_max_char_num <ch_id> <char_num> "`.  
`"update_max_char_num <number> <number>"`.  
***
`"/gm_tool_delete_item_result <ch_id> <gm_name> <item_id> <result>"`.  
`"gm_tool_delete_item_result <number> <word> <number> <number>"`.  
***
`"/gm_tool_add_item_result <ch_id> <ch_name> <gm_name> <item_id> <item_quantity> <result>"`.  
`"gm_tool_add_item_result <number> <word> <word> <number> <number> <number>"`.  
***
`"/clone_monster : clone_monster <id> <unit> <dropid>: Clone Monster At Player around"`.  
`"clone_monster <number> <number> <number>"`.  
`"cm <number> <number> <number>"`.  
***
`"/restore : restore the hp ,mp to the max"`.  
`"restore"`.  
***
`"/set_rb mob <n> <id> <seconds> : reborn mober binding"`.  
`"set_rb <number> <number> <number>"`.  
`"sr <number> <number> <number>"`.  
***
`"/ls_rb : list reborn mober binding"`.  
`"ls_rb"`.  
`"lr"`.  
***
`"/rm_rb mob : remove reborn mober binding"`.  
`"rm_rb <number>"`.  
`"rr <number>"`.  
***
`"/status : query the player's status"`.  
`"status"`.  
***
`"/clone item <item_id>: clone an item which template id is <item_id>"`.  
`"clone_item <number>"`.  
`"ci <number>"`.  
***
`"/clone reward item <item_id> <item_num>: clone an item which template id is <item_id>"`.  
`"clone_reward_item <number> <number>"`.  
`"clri <number> <number>"`.  
***
`"/clone items <item_id> <item_num>: clone an item which template id is <item_id> and item quantity is <item_num>"`.  
`"clone_items <number> <number>"`.  
`"cls <number> <number>"`.  
***
`"/clone items <item_id> <item_num>: clone an item which template id is <item_id> and item quantity is <item_num>"`.  
`"clone_items <number> <number>"`.  
`"clone_stack_item <number> <number>"`.  
***
`"/clone_item_to <item_id> <to_loc>: clone an item which template id is <item_id> and put into inventory at location <to_loc>"`.  
`"clone_item_to <number> <number>"`.  
`"clt <number> <number>"`.  
***
`"/say <message> : say something"`.  
`"say <rest_input>"`.  
`"s <rest_input>"`.  
***
`"/say <message> : say something"`.  
***
`"/whisper <name> <message> : whisper someone something"`.  
`"whisper <word> <rest_input>"`.  
`"w <word> <rest_input>"`.  
***
`"/whisper <name> <message> : whisper someone something"`.  
`"whisper_1 <word> <rest_input>"`.  
***
`"/kill <monster_id> : monster! DIE!"`.  
`"kill <number>"`.  
`"k <number>"`.  
***
`"/gain_exp <word> : gain exp num"`.  
`"gain_exp <word>"`.  
`"ge <word>"`.  
***
`"/gain_gold <word>: gain gold num"`.  
`"gain_gold <word>"`.  
`"gg <word>"`.  
***
`"/goto <x> <y> : goto x y"`.  
`"goto <number> <number>"`.  
***
`"/users : list the node users info"`.  
`"users"`.  
***
`"/allusers: list whole world users"`.  
`"allusers"`.  
***
`"/transfer <id>"`.  
`"transfer <number>"`.  
`"/tf <number>"`.  
***
`"/listarea : list the areas in the currently node"`.  
`"listarea"`.  
`"lsa"`.  
***
`"/weak <player_id> : let target player weak"`.  
***
`"/setra <node_id> <area_id> : set revive area"`.  
`"setra <number> <number>"`.  
`"sra <number> <number>"`.  
***
`"/transport_area <node_id> <area_id> : transport to area"`.  
`"transport_area <number> <number>"`.  
`"tpa <number> <number>"`.  
***
`"/transport_node <node_id> : transport to node"`.  
`"transport_node <number>"`.  
`"tpn <number>"`.  
***
`"/drop_item <item_id> <number> <flag>: drop item"`.  
`"drop_item <number> <number> <rest_input>"`.  
***
`"/list_durability <container_id>: list durability status,equipment:0  inventory:1"`.  
`"list_durability <number>"`.  
`"ld <number>"`.  
***
`"/date", 2.`
***
`"/shop <shop_type> <npc_template_id> <shop_id>: enter shop"`.  
`"shop <word> <number> <number>"`.  
***
`"/shop <shop_type> <npc_id>: enter spell shop"`.  
`"shop <word> <number>"`.  
***
`"/effect_life <life_id> <effect_id> <duration> <factor>"`.  
`"effect_life <number> <number> <number> <number>"`.  
`"elf <number> <number> <number> <number>"`.  
***
`"/effect_loc <x> <y> <effect_id> <duration> <factor>"`.  
`"effect_loc <number> <number> <number> <number> <number>"`.  
`"eloc <number> <number> <number> <number> <number>"`.  
***
`"/repairshop : enter repair shtop"`.  
`"repairshop"`.  
***
`"/invincible <0/1> : invincible mode: 0 - off, 1 - on"`.  
`"invincible <number>"`.  
`"inv <number>"`.  
***
`"/vanish <0/1> : invisible mode: 0 - off, 1 - on"`.  
`"vanish <number>"`.  
`"van <number>"`.  
***
`"/town : transport to town"`.  
***
`"/transport_to_character <given_name>: transport to character with nickname"`.  
`"transport_to_character <word>"`.  
`"tpc <word>"`.  
***
`"/get_user_info <given_name>: findout about an nickname"`.  
`"get_user_info <word>"`.  
`"gui <word>"`.  
***
`"/get_shortcuts: list shortcuts"`.  
`"get_shortcuts"`.  
***
`"/update_shortcut <page> <slot> <value>: modify shortcuts (page and slot starts from 0)"`.  
`"update_shortcut <number> <number> <number>"`.  
`"us <number> <number> <number>"`.  
***
`"/save_shortcut: save shortcuts"`.  
`"save_shortcut"`.  
***
`"/display_sum_node_users <0/1>"`.  
`"display_sum_node_users <number>"`.  
`"dnu <number>"`.  
***
`"/display_sum_world_users <0/1> : list whole world users mode: 0 - off, 1 - on"`.  
`"display_sum_world_users <number>"`.  
`"dwu <number>"`.  
***
`"/get_spellmaster <spellmaster_id> : get a spellmaster"`.  
`"get_spellmaster <number>"`.  
***
`"/debug <0/1> : debug mode: 0 - off, 1 - on"`.  
`"debug <number>"`.  
***
`"/list_state : list my states"`.  
`"list_state"`.  
***
`"/shut_down <minutes>: shut down in x minutes"`.  
`"shut_down <number>"`.  
***
`"/kick <nick_name>: kick out character with name"`.  
`"kick <word>"`.  
***
`"/slayer <0/1> : slayer mode: 0 - off, 1 - on"`.  
`"slayer <number>"`.  
***
`"/announce <message> : announce something"`.  
`"announce <rest_input>"`.  
`"gm <rest_input>"`.  
***
`"/storage <npc_id> <0/1>: enter storage: 0 - Deposit, 1 - Withdraw"`.  
`"storage <number> <number>"`.  
***
`"/querychar <charname>"`.  
`"querychar <word>"`.  
`"qc <word>"`.  
***
`"/look <radius>", 2, "look <number>"`, 
***
`"/listenchant"`.  
***
`"/version"`.  
***
`"/transport_and_deduct <area_id> <money> : transport to area and deduct money"`.  
`"transport_and_deduct <number> <number>"`.  
`"tam <number> <number>"`.  
***
`"/query_npc <node_id> <npc_id>: query npc <number> to show on map"`.  
`"query_npc <number>"`.  
`"qn <number>"`.  
***
`"/party <message> : say something in party channel"`.  
`"party <rest_input>"`.  
`"p <rest_input>"`.  
***
`"/party <message> : say something in party channel"`.  
`"party_2 <rest_input>"`.  
***
`"/guild <message> : say something in guild channel"`.  
`"guild <rest_input>"`.  
`"g <rest_input>"`.  
***
`"/guild <message> : say something in guild channel"`.  
`"guild_3 <rest_input>"`.  
***
`"/trade <message> : say something in trade channel"`.  
`"trade <rest_input>"`.  
`"t <rest_input>"`.  
***
`"/trade <message> : say something in trade channel"`.  
`"trade_4 <rest_input>"`.  
***
`"/chat <message> : say somehting in chat channel"`.  
`"c <rest_input>"`.  
***
`"/chat <message> : say somehting in chat channel"`.  
`"chat_5 <rest_input>"`.  
***
`"/system <message> : announce something from system"`.  
`"system <rest_input>"`.  
***
`"/channel_limit <id> <minute>: channel usage limitation"`.  
`"channel_limit <number> <number>"`.  
`"cl <number> <number>"`.  
***
`"/flush_dba_data: Flush player DBAgent Data"`.  
`"flush_dba_data"`.  
***
`"/banchar <char_id> <minute> : ban character"`.  
`"banchar <number> <number>"`.  
`"bc <number> <number>"`.  
***
`"/identify_shop : enter identify shop"`.  
`"identify_shop"`.  
`"id_shop"`.  
***
`"/disband_family"`.  
***
`"/select_family_leader <new_leader>"`.  
`"select_family_leader <word>"`.  
`"sfl <word>"`.  
***
`"/listfms <ch_id> <mission_id>: list fms info on this character"`.  
`"listfms <number> <number>"`.  
`"lsf <number> <number>"`.  
***
`"/run <number>: Faster Walk"`.  
`"run <number>"`.  
***
`"enter_exchange_item_service"`.  
`"eeis"`.  
***
`"/drop stack item <item_id> <amount> : drop item by amount"`.  
`"drop_items <number> <number>"`.  
`"drop_stack_item <number> <number>"`.  
***
`"/allworld_cmd <rest_input>: all world text command"`.  
`"allworld_cmd <rest_input>"`.  
`"aw <rest_input>"`.  
***
`"/query_npc_involve <npc_id>: query npc <number> to list how many missionlist involved"`.  
`"query_npc_involve <number>"`.  
`"qni <number>"`.  
***
`"/channel_limit_name <charname> <minute>: channel usage limitation"`.  
`"channel_limit_name <word> <number>"`.  
`"cln <word> <number>"`.  
***
`"/banchar_name <char_name> <minute> : ban character"`.  
`"banchar_name <word> <number>"`.  
`"bcn <word> <number>"`.  
***
`"/quest <message> : say somehting in quest channel"`.  
`"quest <rest_input>"`.  
`"q <rest_input>"`.  
***
`"/quest <message> : say somehting in quest channel"`.  
`"quest_6 <rest_input>"`.  
***
`"/reset_attribute : reset attribute point"`.  
`"reset_attribute"`.  
`"ra"`.  
***
`"/reset_skill : reset skill point"`.  
`"reset_skill"`.  
***
`"/reset_attribute_gold <how_much>: reset attribute point for gold"`.  
`"reset_attribute_gold <number>"`.  
`"rag <number>"`.  
***
`"/reset_skill_gold <how_much>: reset skill point for gold"`.  
`"reset_skill_gold <number>"`.  
`"rsg <number>"`.  
***
`"/get_spell <spell_id> : get a spell"`.  
`"get_spell <number>"`.  
***
`"/inlay_shop <npc_id>: enter inlay shop"`.  
`"inlay_shop <number>"`.  
`"in_shop <number>"`.  
***
`"/broadcast_system_message <msg_id> <times> <interval> <msg>"`.  
`"broadcast_system_message <number> <number> <number> <rest_input>"`.  
`"bsm <number> <number> <number> <rest_input>"`.  
***
`"/echo <message>: show message without prompt"`.  
`"echo <rest_input>"`.  
***
`"/clone_monster_locate <mob_id> <absolute> <loc_x> <loc_y>: clone monster in absolute/relate coordinate in same node with player"`.  
`"clone_monster_locate <number> <number> <number> <number>"`.  
`"cml <number> <number> <number> <number>"`.  
***
`"/clone_monster_around <mob_id> <absolute> <angle> <range>: clone monster around player by absolute/relate angle"`.  
`"clone_monster_around <number> <number> <number> <number>"`.  
`"cma <number> <number> <number> <number>"`.  
***
`"/npc_use_channel <npc_id> <channel_id> <message>: let npc use channel to say something"`.  
`"npc_use_channel <number> <number> <rest_input>"`.  
`"nuc <number> <number> <rest_input>"`.  
***
`"/npc_use_spell <npc_id> <spell_id>: let npc use spell on pc in the same node"`.  
`"npc_use_spell <number> <number>"`.  
`"nus <number> <number>"`.  
***
`"/self_use_effect <effect_id> <duration>: let pc use effect on self"`.  
`"self_use_effect <number> <number>"`.  
`"sue <number> <number>"`.  
***
`"/askvendor : ask vendor "`.  
`"askvendor"`.  
***
`"/change_class <class_id>: change current class"`.  
`"change_class <number>"`.  
`"cc <number>"`.  
***
`"/adjust_spell_anitime <spell_id> <animeTime_ofs>: change spell animation time"`.  
`"adjust_spell_anitime <number> <number>"`.  
`"asa <number> <number>"`.  
***
`"/escape : transfer team member to the last enter normal area"`.  
`"escape"`.  
`"esc"`.  
***
`"/set_level <level> : set character level,"`.  
`"set_level <number>"`.  
`"sl <number>"`.  
***
`"/set_monster_damage <monster id> <physico damage> <attack var> <physico defence> <magic damage> <magic attack var> <magic defence>: set monster damage,"`.  
`"set_monster_damage <number> <number> <number> <number> <number> <number> <number>"`.  
`"smd <number> <number> <number> <number> <number> <number> <number>"`.  
***
`"/set_monster_movement <monster id> <movement> <roammovement> <attack delay>: set monster "`.  
`"set_monster_movement <number> <number> <number> <number>"`.  
`"smm <number> <number> <number> <number>"`.  
***
`"/show_monster <template monster id>  : show monster information"`.  
`"show_monster <number>"`.  
`"sm <number>"`.  
***
`"/set_monster_sight <monster id> <sight> : set monster sight"`.  
`"set_monster_sight <number> <number>"`.  
`"sms <number> <number>"`.  
***
`"/test_character_attack <monster id> : test character "`.  
`"test_character_attack <number> <number>"`.  
`"tca <number> <number>"`.  
***
`"/test_monster_attack <monster id> : test monster "`.  
`"test_monster_attack <number> <number>"`.  
`"tma <number> <number>"`.  
***
`"/set_sevel_grow <con> <str> <int> <dex> <vol> <max_hp> <max_mp>: set attr "`.  
`"set_level_grow <number> <number> <number> <number> <number> <number> <number>"`.  
***
`"/querylevelgrow "`.  
`"query_level_grow"`.  
`"qlg"`.  
***
`"/queryequipment"`
***
`"/set_item <item id> <word> <number>"`.  
`"set_item <number> <word> <number>"`.  
***
`"/save_monster <template monster id>  : save monster to db"`.  
`"save_monster <number>"`.  
***
`"/get_effect_data <effect id> : get effect data"`.  
`"get_effect_data <number>"`.  
`"ged <number>"`.  
***
`"/set_effect_data <effect id> <family type> <target type> <duration> <period> <width> <height> <enchant type> <resist type> <param min> <param max> <next id> <level> : set effect data"`.  
`"set_effect_data <number> <word> <word> <number> <number> <number> <number> <word> <word> <number> <number> <number> <number>"`.  
`"sed <number> <word> <word> <number> <number> <number> <number> <word> <word> <number> <number> <number> <number>"`.  
***
`"/set_effect_command <effect id> <command type> <commands> : set effect command"`.  
`"set_effect_command <number> <word> <rest_input>"`.  
`"sec <number> <word> <rest_input>"`.  
***
`"/get_spell_data <spell id> : get spell data"`.  
`"get_spell_data <number>"`.  
`"gsd <number>"`.  
***
`"/set_reborn_monster <handle> <x> <y> <monster_temp_id> <amount> <seconds> <width> <height> <patrol_id>: reborn mober binding"`.  
`"set_reborn_monster <number> <word> <word> <number> <number> <number> <word> <word> <number>"`.  
`"srm <number> <word> <word> <number> <number> <number> <word> <word> <number>"`.  
***
`"/get_all_template_monsters : get all template monster"`.  
`"get_all_template_monsters"`.  
`"gatm"`.  
***
`"/monster_goto <monster id> <x> <y> : goto x y"`.  
`"monster_goto <number> <number> <number>"`.  
`"wm <number> <number> <number>"`.  
***
`"/around_kill_all <radius> : around kill all"`.  
`"around_kill_all <number>"`.  
`"aka <number>"`.  
***
`"/around_kill <monster id> <radius> : around kill "`.  
`"around_kill <number> <number>"`.  
`"ak <number> <number>"`.  
***
`"/query_test_attack_monster : query test attack monster "`.  
`"query_test_attack_monster"`.  
`"qtam"`.  
***
`"/reload_reborn_monster <node id> : reload reborn monster"`.  
`"reload_reborn_monster <number>"`.  
`"rrm <number>"`.  
***
`"/list_pms <pms_id>: list pms info on this character"`.  
`"listpms <number>"`.  
***
`"/echobyid <greeting_id>: show message without prompt by greeting_id"`.  
`"echobyid <number>"`.  
***
`"/change_hair_color <color_id> : change character hair color"`.  
`"change_hair_color <number>"`.  
`"chc <number>"`.  
***
`"/change_hair <hair_id> : change character hair"`.  
`"change_hair <number>"`.  
`"ch <number>"`.  
***
`"/reload_effect : reload effect data"`.  
`"reload_effect"`.  
***
`"/reload_template_monster : reload template_monster data"`.  
`"rtm"`.  
***
`"/summon_pet <template_id>: summon pet"`.  
`"summon_pet <number>"`.  
***
`"/gain_skill_point <number>: gain skill point"`.  
`"gain_skill_point <number>"`.  
`"gsp <number>"`.  
***
`"/node <message> : say to all man in node"`.  
`"node <rest_input>"`.  
`"n <rest_input>"`.  
***
`"/system_area <area_id> <message> : announce something from system"`.  
`"system_area <word> <rest_input>"`.  
`"sysarea <word> <rest_input>"`.  
***
`"/fatality_damage <LiftEntity_id> : set LiftEntity HP = MP = 1"`.  
`"fatality_damage <number>"`.  
`"fd <number>"`.  
***
`"/restore_all : restore the hp ,mp to the max on players around caster"`.  
`"restore_all"`.  
***
`"/clear_near_items : clear near items around caster"`.  
`"clear_near_items"`.  
`"cni"`.  
***
`"/get_server_id : get zoneserver id"`.  
`"get_server_id"`.  
`"gsi"`.  
***
`"/test_durability <mob id> <loc> <durability>: test durability decrease in attacked"`.  
`"test_durability <number> <number> <number>"`.  
`"td <number> <number> <number>"`.  
***
`"/test_spell_attack <monster id> <spell id> <number>: test character "`.  
`"test_spell_attack <number> <number> <number>"`.  
`"tsa <number> <number> <number>"`.  
***
`"/test_drop_treasure <monster id> <number>: test drop treasure "`.  
`"test_drop_treasure <number> <number>"`.  
`"tdt <number> <number>"`.  
***
`"/test_pk <monster id> : test pk "`.  
`"test_pk <number> <number>"`.  
`"tpk <number> <number>"`.  
***
`"/surprise_box <SurpriseBoxID> : invoke surprise box"`.  
`"surprise_box <number>"`.  
`"sb <number>"`.  
***
`"/SetExtBornMonster <num> <time sec>: extern born monster"`.  
`"setextbornmonster <number> <number>"`.  
`"sebm <number> <number>"`.  
***
`"/set_family_level <fm_level> : set family level"`.  
`"set_family_level <number>"`.  
`"sflv <number>"`.  
***
`"/family_level_up : family level up"`.  
`"family_level_up"`.  
`"flu"`.  
***
`"/set_family_emblem <emblem1> <emblem2> : set family emblem"`.  
`"set_family_emblem <number> <number>"`.  
`"sfe <number> <number>"`.  
***
`"/select_family_emblem : select family emblem"`.  
`"select_family_emblem"`.  
***
`"/reload_formula_params : reload formula parameters"`.  
`"reload_formula_params"`.  
***
`"/reload_grow_table : reload grow table"`.  
`"reload_grow_table"`.  
***
`"/SetStallSpace <num> : SetStallSpace"`.  
`"setstallspace <number>"`.  
`"sss <number>"`.  
***
`"/SetStallSignboard <num> : SetStallSignboard"`.  
`"setstallsignboard <number>"`.  
`"sssb <number>"`.  
***
`"/give_exploit <exploit amount>"`.  
`"give_exploit <number>"`.  
***
`"/RepairAllEquipment: RepairAllEquipment"`.  
`"repairallequipment"`.  
`"rae"`.  
***
`"/Ping: Ping", 0, "ping"`.  
***
`"/trace <receive_id> <target_name> : Trace a character by name"`.  
`"trace <number> <word>"`.  
***
`"/drill_item <slot> <number>: DrillItem"`.  
`"drill_item <number> <number>"`.  
***
`"/fubag <id> : fortune bag item"`.  
`"fubag <number>"`.  
***
`"/aw_put_treasure <id> <amount>: put treasure all world"`.  
`"aw_put_treasure <number> <number>"`.  
`"awpt <number> <number>"`.  
***
`"/setfms <ch_id> <mission_id> <value>: set fms value on this character"`.  
`"setfms <number> <number> <number>"`.  
`"setf <number> <number> <number>"`.  
***
`"/clone_quest_treasure <item_id> <number> <node_id> <x> <y> <template_id>: drop quest item"`.  
`"clone_quest_treasure <number> <number> <number> <number> <number> <number>"`.  
***
`"/set_bag_time <index> <time>: set the due date for bags"`.  
`"set_bag_time <number> <number>"`.  
`"sbt <number> <number>"`.  
***
`"/gain_crystal <amount>: gain crystal num"`.  
`"gain_crystal <number>"`.  
`"gc <number>"`.  
***
`"/gain_family_exp <number>: gain family exp"`.  
`"gain_family_exp <number>"`.  
`"gfe <number>"`.  
***
`"/set_prestige_level <prestige_id> <level>: set prestige level"`.  
`"set_prestige_level <number> <number>"`.  
`"spl <number> <number>"`.  
***
`"/gain_prestige_exp <prestige_id> <exp>: gain prestige exp"`.  
`"gain_prestige_exp <number> <number>"`.  
`"gpe <number> <number>"`.  
***
`"/cast_spell <number> <number>: cast spell to life"`.  
`"cast_spell <number> <number>"`.  
`"cs <number> <number>"`.  
***
`"/set_sys_var <word> <number> : set system varaible"`.  
`"set_sys_var <word> <number>"`.  
`"ssv <word> <number>"`.  
***
`"/add_appellation <appellation_id> : add appellation"`.  
`"add_appellation <number>"`.  
`"aa <number>"`.  
***
`"/set_present_appellation <appellation_id> : set present appellation"`.  
`"set_present_appellation <number>"`.  
`"spa <number>"`.  
***
`"/add_elf <elf_id> : add elf"`.  
`"add_elf <number>"`.  
`"ae <number>"`.  
***
`"/elf_work <elf_loc> <work_type> <work_id> <item_index> <item_loc>: elf work"`.  
`"elf_work <number> <number> <number> <number> <number>"`.  
`"ew <number> <number> <number> <number> <number>"`.  
***
`"/remove_elf <elf_loc> : remove elf"`.  
`"remove_elf <number>"`.  
***
`"elf_skill <add:1/remove:0> <elf_loc> <skill_id> : elf skill"`.  
`"elf_skill <number> <number> <number>"`.  
***
`"set_elf_level <level>: set first elf level"`.  
`"set_elf_level <number>"`.  
***
`"set_elf_mood <elf_loc> <mood>: set elf mood"`.  
`"set_elf_mood <number> <number>"`.  
`"sem <number> <number>"`.  
***
`"use_item_to <inv/equ> <container_index> <loc> <target_id> <param>: use item to"`.  
`"use_item_to <word> <number> <number> <number> <rest_input>"`.  
`"uit <word> <number> <number> <number> <rest_input>"`.  
***
`"set_spell_card <index> <item_number>"`.  
`"set_spell_card <number> <number>"`.  
`"ssc <number> <number>"`.  
***
`"gain_elf_exp <elf_loc> <exp>: gain elf exp"`.  
`"gain_elf_exp <number> <number>"`.  
`"gee <number> <number>"`.  
***
`"gain_elf_familiar <elf_loc> <familiar>: gain elf familiar"`.  
`"gain_elf_familiar <number> <number>"`.  
`"gef <number> <number>"`.  
***
`"show_debug_message <0/1>: show debug message"`.  
`"show_debug_message <number>"`.  
`"sdm <number>"`.  
***
`"set_log_level <server> <level>: set server(m/w/z/all) log level"`.  
`"set_log_level <word> <number>"`.  
`"slog <word> <number>"`.  
***
`"set_assert <server> <0/1>: set server(m/w/z/all) assert: 0 - off, 1 - on"`.  
`"set_assert <word> <number>"`.  
***
`"set_spell_card_attr <value> <value> <value> <value> : set spell card attr "`.  
`"set_spell_card_attr <number> <number> <number> <number>"`.  
***
`"set_elf_action <loc> <animation_id> : set elf action "`.  
`"set_elf_action <number> <number> "`.  
`"sea <number> <number>"`.  
***
`"inside <class> : test some information"`.  
`"inside <number>"`.  
***
`"auction_sell <item_id> <amount> : auction sell "`.  
`"auction_sell <number> <number> "`.  
`"as <number> <number>"`.  
***
`"friend_together : player add frined"`.  
`"friend_together"`.  
***
`"reload_itemmall_db : reload itemmall db"`.  
`"reload_itemmall_db"`.  
`"rid"`.  
***
`"set_node_exp : set node exp rate"`.  
`"set_node_exp <number> <number>"`.  
`"sne <number> <number>"`.  
***
`"set_node_gold : set node gold rate"`.  
`"set_node_gold <number> <number>"`.  
`"sng <number> <number>"`.  
***
`"set_node_drop : set node drop rate"`.  
`"set_node_drop <number> <number>"`.  
`"snd <number> <number>"`.  
***
`"show_hate : Show Character All Hate"`.  
`"show_hate"`.  
***
`"/clone item <item_id> <combo_id>: clone an item which template id is <item_id> and combo id is <combo_id>"`.  
`"clone_item <number> <number>"`.  
`"ci <number> <number>"`.  
***
`"/clone item <item_id> <combo_id> <socket_amount>: clone an item which template id is <item_id> and combo id is <combo_id>, socket amount <socket_amount>"`.  
`"clone_item <number> <number> <number>"`.  
`"ci <number> <number> <number>"`.  
***
`"/return item <receiver_id> <log>: use mail return an item to player from log"`.  
`"return_item <number> <rest_input>"`.  
`"ri <number> <rest_input>"`.  
***
`"/call elf <loc>: call elf which loc is <loc>"`.  
`"call_elf <number>"`.  
***
`"/return gold <receiver_id> <gold>: use mail return gold to player"`.  
`"return_gold <number> <word>"`.  
`"rg <number> <word>"`.  
***
`"battlefield <0/1>: 0 - off, 1 - on"`.  
`"bf <number>"`.  
***
`"/gain aa point <point>: gain advanced ability point"`.  
`"gain_aa_point <number>"`.  
`"gaap <number>"`.  
***
`"/gain aa exp <exp>: gain advanced ability exp"`.  
`"gain_aa_exp <number>"`.  
***
`"/set aa rate <rate>: set advanced ability gain exp rate"`.  
`"set_aa_rate <number>"`.  
`"saar <number>"`.  
***
`"/reset aa : reset advanced ability"`.  
`"reset_aa"`.  
***
`"/clone_npc <npc_id>: clone npc"`.  
`"clone_npc <number>"`.  
`"cn <number>"`.  
***
`"/around_kill_all_player <radius> : around kill all player"`.  
`"around_kill_all_player <number>"`.  
`"akap <number>"`.  
***
`"/gain_family_treasury <money>: gain family treasury"`.  
`"gain_family_treasury <number>"`.  
`"gft <number>"`.  
***
`"/adopt_elf_king <template_id> : adopt elf king"`.  
`"adopt_elf_king <number>"`.  
`"aek <number>"`.  
***
`"/captcha_id <id> <type>: captcha_id <id> <type>"`.  
`"captcha_id <number> <number>"`.  
`"capid <number> <number>"`.  
***
`"/captcha_name <given_word> <type>: captcha_name <given_name> <type>"`.  
`"captcha_name <word> <number>"`.  
`"capname <word> <number>"`.  
***
`"/clear_bag_item: clear bag item"`.  
`"clear_bag_item"`.  
***
`"/gain_elfking_point <point> : gain elfking point"`.  
`"gain_elfking_point <number>"`.  
`"gep <number>"`.  
***
`"/set_statue <node> <id> <action> <key>: set statue"`.  
`"set_statue <number> <number> <number> <number>"`.  
`"sst <number> <number> <number> <number>"`.  
***
`"/bf_ch_num <bf_type> <level_type> <number> : bf_ch_num"`.  
`"bf_ch_num <number> <number> <number>"`.  
***
`"/bf_open <open> <bf_today_type> : bf_open"`.  
`"bf_open <number> <number>"`.  
***
`"/show_op : show character operation"`.  
`"show_op"`.  
***
`"send_sys_mail_queue <number>"`.  
`"ssmq <number>"`.  
***
`"/clear_cool_down_time : clear character's cool down time"`.  
`"clear_cool_down_time"`.  
`"ccdt"`.  
***
`"/family_battle <number>"`.  
***
`"/city_owner <number>"`.  
***
`"/ping_name <word>"`.  
***
`"set_spell_card_attr <value> <value> <value> <value> <value> <value> <value> <value> : set spell card attr "`.  
`"set_spell_card_attr <number> <number> <number> <number> <number> <number> <number> <number>"`.  
***
`"transport_to_npc <value> : transport to npc "`.  
`"transport_to_npc <number>"`.  
`"tpnpc <number>"`.  
***
`"elf_skill_level <elf_loc> <skill_index> <level> <exp>: elf skill"`.  
`"elf_skill_level <number> <number> <number> <number>"`.  
***
`"set_bot <open>: set first elf bot open"`.  
`"set_bot <number>"`.  
***
`"gain_elfgame_skill <number> <number>: gain elfgame skill exp"`.  
`"gain_elfgame_skill <number> <number>"`.  
`"ges <number> <number>"`.  
***
`"/announce_zone <message> : announce something"`.  
`"announce_zone <rest_input>"`.  
***
`"/gm_tell <name> <message> : tell someone something"`.  
`"gm_tell <word> <rest_input>"`.  
`"gmt <word> <rest_input>"`.  
***
`"/reload_elf_lottery_db : reload elf lottery db"`.  
`"reload_elf_lottery_db"`.  
`"reld"`.  
***
`"/remove_enchant <player_id> <enchant_id> : Remove Player Enchant"`.  
`"remove_enchant <number> <number>"`.  
***
`"/add_enchant <player_id> <enchant_id> <dur_time>: Add Player Enchant"`.  
`"add_enchant <number> <number> <number>"`.  
***
`"/set_lucky_star_bonus <number>: set lucky star bonus"`.  
`"set_lucky_star_bonus <number>"`.  
`"slsb <number>"`.  
***
`"/lucky_star_draw <time> <number1> <number2> <number3> <number4> <number5> <special_no>: draw lucky star with indicated numbers"`.  
`"lucky_star_draw <number> <number> <number> <number> <number> <number> <number>"`.  
`"lsd <number> <number> <number> <number> <number> <number> <number>"`.  
***
`"/lucky_star_draw_auto <time>: draw lucky star automatically"`.  
`"lucky_star_draw_auto <number>"`.  
`"lsda <number>"`.  
***
`"/lucky_star_update: force lucky stat finished maintenance"`.  
`"lucky_star_update"`.  
`"lsu"`.  
***
`"/lucky_bar_status: show lucky bar elf's money"`.  
`"lucky_bar_status"`.  
`"lbs"`.  
***
`"/lucky_bar_show_dice <number>: show lucky bar dice result"`.  
`"lucky_bar_show_dice <number>"`.  
`"lbsd <number>"`.  
***
`"/lucky_bar_set_money <number>: set lucky bar money"`.  
`"lucky_bar_set_money <number>"`.  
***
`"/minigame_shutdown <number>: set minigame shutdown"`.  
`"minigame_shutdown <number>"`.  
***
`"/gain_fortune_coin <number>: get fortune coin"`.  
`"gain_fortune_coin <number>"`.  
`"gfc <number>"`.  
***
`"/add_luckystart_bounds <number>: add lucky star bounds"`.  
`"add_luckystart_bounds <number>"`.  
***
`"/screenmessage <type> <msg> : screen message"`.  
`"screenmessage <number> <rest_input>"`.  
***
`"/screenmessage_index <type> <index> : screen message"`.  
`"screenmessage_index <number> <number>"`.  
***
`"/add_enchant <player_id> <enchant_id> <dur_time> <isteam> : Add Player or Team Enchant"`.  
`"add_enchant <number> <number> <number> <number>"`.  
***
`"/remove_enchant <player_id> <enchant_id> <isteam>: Remove Player or Team Enchant"`.  
`"remove_enchant <number> <number> <number>"`.  
***
`"/transfer_by_name <given_name>: character with nickname transport to caller "`.  
`"transfer_by_name <word>"`.  
`"tbn <word>"`.  
***
`"/get_net_cafe_vip <player_id> <type>: get net cafe vip"`.  
`"get_net_cafe_vip <number> <number>"`.  
`"gncv <number> <number>"`.  
***
`"/event_achievement <achi_id> <point> <isteam>"`.  
`"event_achievement <number> <number> <number>"`.  
***
`"/elf_team_fight_killed <monster_id>: elf team fight killed"`.  
`"elf_team_fight_killed <number>"`.  
`"etfk <number>"`.  
***
`"/set_gm_map_open <node_id> <open>: set gm map open"`.  
`"set_gm_map_open <number> <number>"`.  
`"sgmmo <number> <number>"`.  
***
`"/elf_boxing <item_id> <item_id> <times>: elf boxing test"`.  
`"elf_boxing <number> <number> <number>"`.  
`"eb <number> <number> <number>"`.  
***
`"/elf_boxing_bet <bet_1> <bet_2> <bet_3> <bet_4>: elf boxing bet"`.  
`"elf_boxing_bet <number> <number> <number> <number>"`.  
`"ebb <number> <number> <number> <number>"`.  
***
`"/elf_boxing_show_bets: elf boxing show bets"`.  
`"elf_boxing_show_bets"`.  
`"ebs"`.  
***
`"/set_blocklogin <char_id> <flag_id>: set block login value"`.  
`"set_blocklogin <number> <number>"`.  
`"sbl <number> <number>"`.  
***
`"/set_useblocklogin <flag_id>: set use block login value"`.  
`"set_useblocklogin <number>"`.  
`"subl <number>"`.  
***
`"/refresh_recommended_events <number> : refresh_recommended_events"`.  
`"refresh_recommended_events <number>"`.  
`"rre <number>"`.  
***
`"/set_all_missionbook_open <open>: set all missionbook open"`.  
`"set_all_missionbook_open <number>"`.  
`"smbo <number>"`.  
***
`"/npc_option <npc_id> <cmd_index> <switch>: set all missionbook open"`.  
`"npc_option <number> <number> <number>"`.  
`"no <number> <number> <number>"`.  
***
`"/countdown_msg <start_tim> <time_seconds> <msg>: Countdown Msg"`.  
`"countdown_msg <number> <number> <rest_input>"`.  
`"cdm <number> <number> <rest_input>"`.  
***
`"/show_countdown_msg: Show Countdown Msg"`.  
`"show_countdown_msg"`.  
`"show_cdm"`.  
***
`"/del_countdown_msg: Delete Countdown Msg"`.  
`"del_countdown_msg"`.  
`"del_cdm"`.  
***
`"/show_countdown_msg <number>: Show Countdown Msg"`.  
`"show_countdown_msg <number>"`.  
`"show_cdm <number>"`.  
***
`"/restart_family_battle_rank: Restart FamilyBattle Rank"`.  
`"rfbrank"`.  
***
`"/reload_gm_cmd_ini: Reload GMCmd.ini"`.  
`"reload_gm_cmd_ini"`.  
`"rgci"`.  
***
`"/set_max_char_num <ch_id> <max_num>: Set Max Char Num"`.  
`"set_max_char_num <number> <number>"`.  
`"smcn <number> <number>"`.  
***
`"/clear_storage_itemmall: Clear Storage ItemMall"`.  
`"clear_storage_itemmall"`.  
`"csi"`.  
***
`"/kill_npc <npc_id> <node_id>: Kill Npc"`.  
`"kill_npc <number> <number>"`.  
`"kn <number> <number>"`.  
***
`"/elf_game_invite_player <target_id>: Elf Game Invite Player"`.  
`"elf_game_invite_player <number>"`.  
`"egip <number>"`.  
***
`"/look_npc <radius>: Look Npc"`.  
`"look_npc <number>"`.  
`"ln <number>"`.  
***
`"/kill_npc_by_id <npc_sid>: Kill npc by serial number"`.  
`"kill_npc_by_id <number>"`.  
`"kn <number>"`.  
***
`"/reload_translate <t_name>: Reload Translate"`.  
`"reload_translate <word>"`.  
`"rlt <word>"`.  
***
`"/reload_translate <t_name> <id>: Reload Translate"`.  
`"reload_translate <word> <number>"`.  
`"rlt <word> <number>"`.  
***
`"/gain_lover_coin <number> <id>: Gain lover coins"`.  
`"gain_lover_coin <number>"`.  
`"glc <number>"`.  
***
`"/set_territory_open <territory_tid> <duration>: set_territory_open"`.  
`"set_territory_open <number> <number>"`.  
***
`"/gbf_set: gbf_set"`.  
***
`"/set_territory_close <territory_tid>: set_territory_close"`.  
`"set_territory_close <number>"`.  
`"tc <number>"`.  
***
`"/set_elf_class <class_id>: set_elf_class"`.  
`"set_elf_class <number>"`.  
`"sec <number>"`.  
***
`"/elf_ai <ai_id>: elf_ai"`.  
`"elf_ai <number>"`.  
`"eai <number>"`.  
***
`"/set_elf_spell <ai_id>: set_elf_spell"`.  
`"set_elf_spell <number>"`.  
`"ses <number>"`.  
***
`"/bf_finish <dur_index>: bf_finish"`.  
`"bf_finish <number>"`.  
`"bff <number>"`.  
***
`"/bf_ch_count <by_type> <level>: bf_ch_count"`.  
`"bf_ch_count <number> <number>"`.  
`"bcc <number> <number>"`.  
***
`"/reset_itemmall_limit <account_id>: reset_itemmall_limit"`.  
`"reset_itemmall_limit <number>"`.  
`"riml <number>"`.  
***
`"/isle_add_statue <mon_id>: isle_add_statue"`.  
`"isle_add_statue <number>"`.  
`"ias <number>"`.  
***
`"/isle_add_altar <elf_id>: isle_add_altar"`.  
`"isle_add_altar <number>"`.  
***
`"/isle_set_level <level>: isle_set_level"`.  
***
`"/del_isle: del_isle"`.  
***
`"/isle_enable <enable>: isle_enable"`.  
`"isle_enable <number>"`.  
`"isle_enable <number>"`.  
***
`"/lucky_bar_show_record: lucky_bar_show_record"`.  
`"lucky_bar_show_record"`.  
`"lbsr"`.  
***
`"/start_family_battle <enable>: start_family_battle"`.  
`"start_family_battle <number>"`.  
***
`"/gain_eq_exp <exp>: gain_eq_exp"`.  
`"gain_eq_exp <number>"`.  
`"geqe <number>"`.  
***
`"/set_eq_level <level>: set_eq_level"`.  
`"set_eq_level <number>"`.  
`"seql <number>"`.  
***
`"/show_lotterygo_item: show_lotterygo_item"`.  
`"show_lotterygo_item"`.  
`"slgi"`.  
***
`"/lottery_go_show <show>: lottery_go_show"`.  
`"lottery_go_show <number>"`.  
`"lgs <number>"`.  
***
`"/lottery_go_open <open>: lottery_go_open"`.  
`"lottery_go_open <number>"`.  
`"lgo <number>"`.  
***
`"/set_lover_mood <mood>: set_lover_mood"`.  
`"set_lover_mood <number>"`.  
`"slm <number>"`.  
***
`"/list_family_members <fid>: list_family_members"`.  
`"list_family_members <number>"`.  
`"lfm <number>"`.  
***
`"/set_family_member_privilege <chid> <privilege>: set_family_member_privilege"`.  
`"set_family_member_privilege <number> <number>"`.  
`"sfmp <number> <number>"`.  
***
`"/remove_family <fid>: remove_family"`.  
`"remove_family <number>"`.  
`"rf <number>"`.  
***
`"/transport_character_to_revive_area <chid>: transport_character_to_revive_area"`.  
`"transport_character_to_revive_area <number>"`.  
`"tctra <number>"`.  
***
`"/set_lover_days <days>: set_lover_days"`.  
`"set_lover_days <number>"`.  
`"sld <number>"`.  
***
`"/show_lover_mood: show_lover_mood"`.  
`"show_lover_mood"`.  
`"shlm"`.  
***
`"/get_all_collection: get_all_collection"`.  
`"get_all_collection"`.  
`"gac"`.  
***
`"/show_me_answer: show_me_answer"`.  
`"show_me_answer"`.  
`"sma"`.  
***
`"/trigger_dynamic_event <chid> <event> <type> <state>: trigger_dynamic_event"`.  
`"trigger_dynamic_event <number> <number> <number> <number>"`.  
`"tde <number> <number> <number> <number>"`.  
***
`"/chang_npc_template <npcid> <tid> <handle>: chang_npc_template"`.  
`"chang_npc_template <number> <number> <number>"`.  
`"cnt <number> <number> <number>"`.  
***
`"/clear_elf_bag_item: clear elf bag item"`.  
`"clear_elf_bag_item"`.  
`"cebi"`.  
***
`"/open_fortune_bag <fortune_bag_id> <times>"`.  
`"open_fortune_bag <number> <number>"`.  
`"ofb <number> <number>"`.  
***
`"/gain_re_star <star_num>"`.  
`"gain_re_star <number>"`.  
`"gres <number>"`.  
***
`"/gain_mounts_exp <exp>: gain_mounts_exp"`.  
`"gain_mounts_exp <number>"`.  
`"gme <number>"`.  
***
`"/set_mounts_level <level>: set_mounts_level"`.  
`"set_mounts_level <number>"`.  
`"sml <number>"`.  
***
`"/transport_area_ex <node_id> <area_id> <lv>: transport to area"`.  
`"transport_area_ex <number> <number> <number>"`.  
`"tpaex <number> <number> <number>"`.  
***
`"/enable_isle_change_name <ch_id> <enable>: enable isle change name"`.  
`"enable_isle_change_name <number> <number>"`.  
`"eicn <number> <number>"`.  
***
`"/close_node <node_tid> <enable>: enable node"`.  
`"close_node <number> <number>"`.  
`"cnd <number> <number>"`.  
***
`"/gain_elf_skill_point <level> <point>: gain elf spell point"`.  
`"gain_elf_skill_point <number> <number>"`.  
`"gesp <number> <number>"`.  
***
`"/gain_elf_skill_exp <level> <exp>: gain elf spell exp"`.  
`"gain_elf_skill_exp <number> <number>"`.  
`"gese <number> <number>"`.  
***
`"/all_mission_ready_ok <name> <enable>: all mission ready ok"`.  
`"all_mission_ready_ok <word> <number>"`.  
`"amro <word> <number>"`.  
***
`"/drop_item_test <monster_id> <count>: drop item test"`.  
`"drop_item_test <number> <number>"`.  
`"dit <number> <number>"`.  
***
`"/show_boxing_bonus : show_boxing_bonus"`.  
`"show_boxing_bonus"`.  
`"sbb"`.  
***
`"/add_boxing_bonus <number> <number> : add_boxing_bonus"`.  
`"add_boxing_bonus <number> <number>"`.  
`"abb <number> <number>"`.  
***
`"/boxing_all_win <number> : boxing_all_win"`.  
`"boxing_all_win <number>"`.  
`"baw <number>"`.  
***
`"/clear_gladiator_play_limit : clear_gladiator_play_limit"`.  
`"clear_gladiator_play_limit"`.  
`"cgpl"`.  
***
`"/set_race_number <number> : set_race_number"`.  
`"set_race_number <number>"`.  
`"srn <number>"`.  
***
`"/kick_race_member <word> : kick_race_member"`.  
`"kick_race_member <word>"`.  
`"krm <word>"`.  
***
`"/restart_achievement_rank : restart_achievement_rank"`.  
`"restart_achievement_rank"`.  
`"rar"`.  
***
`"/add_all_appellation : add_all_appellation"`.  
`"aaa"`.  
***
`"/clone_item_range <begin_item_id> <end_item_id>: clone items which template id is <item_id> to <item_id>"`.  
`"clone_item_range <number> <number>"`.  
`"cir <number> <number>"`.  
***
`"/get_reaward_open <enable>: get_reaward_open"`.  
`"get_reaward_open <number>"`.  
***
`"/get_reaward_show <enable>: get_reaward_show"`.  
`"get_reaward_show <number>"`.  
***
`"/set_ride <id>: set_ride"`.  
`"set_ride <number>"`.  
`"sr <number>"`.  
***
`"/ride_point <point>: ride_point"`.  
`"ride_point <number>"`.  
***
`"/open_staravenue <enable>: open_staravenue"`.  
`"open_staravenue <number>"`.  
`"osa <number>"`.  
***
`"/set_staravenue_text <text>: set_staravenue_text"`.  
`"set_staravenue_text <rest_input>"`.  
`"ssat <rest_input>"`.  
***
`"/gain_tree_energy <energy>: gain_tree_energy"`.  
`"gain_tree_energy <number>"`.  
`"gte <number>"`.  
***
`"/gain_tree_exp <exp>: gain_tree_exp"`.  
`"gain_tree_exp <number>"`.  
`"gtexp <number>"`.  
***
`"/gain_free_ticket <count>: gain_free_ticket"`.  
`"gain_free_ticket <number>"`.  
`"gftk <number>"`.  
***
`"/set_memory_recycle <number> <number> <number>"`.  
`"set_memory_recycle <number> <number> <number>"`.  
***
`"isle_clearcdtime: clear isle cd"`.  
`"isle_clearcdtime"`.  
***
`"gain_mentor_points <pts>: gain_mentor_points"`.  
`"gain_mentor_points <number>"`.  
`"gmp <number>"`.  
***
`"gain_mentor_level <rank>: gain_mentor_level"`.  
`"gain_mentor_level <number>"`.  
`"gmlv <number>"`.  
***
`"reset_mentorship_instance <player_name> : reset_mentorship_instance"`.  
`"reset_mentorship_instance <word>"`.  
`"rmi <word>"`.  
***
`"set_mentorship_progress <progress> : set_mentorship_progress"`.  
`"set_mentorship_progress <number>"`.  
`"smp <number>"`.  
***
`"set_reincarnation <flag>: set_reincarnation"`.  
`"set_reincarnation <number>"`.  
***
`"set_runningelf_round <elf_ids> <bet_multiple> <bet_type> <bet_idx> <bet_count> <skip> : set_runningelf_round"`.  
`"set_runningelf_round <word> <number> <number> <number> <number> <number>"`.  
`"srr <word> <number> <number> <number> <number> <number>"`.  
***
`"show_runningelf_speeds: show_runningelf_speeds"`.  
`"show_runningelf_speeds"`.  
`"srs"`.  
***
`"show_scene_event_state: show_scene_event_state"`.  
`"show_scene_event_state"`.  
***
`"set_db_fms <ch_name> <mission_id> <mission_type> : set_db_fms"`.  
`"set_db_fms <word> <number> <number>"`.  
***
`"check_fms_db <ch_name> <mission_id> : check_fms_db"`.  
`"check_fms_db <word> <number>"`.  
***
`"mission_reward_complete"`.  
`"mission_reward_complete"`.  
***
`"gain_battlefield_score <side> <score>: gain_battlefield_score"`.  
`"gain_battlefield_score <number> <number>"`.  
`"gbs <number> <number>"`.  
***
`"show_item_id <switch>: show_item_id"`.  
`"show_item_id <number>"`.  
`"sii <number> "`.  
***
`"bt_option <switch>: bt_option"`.  
`"bt_option <number>"`.  
`"bto <number> "`.  
***
`"bt_set_challenge <ch> <count>: bt_set_challenge"`.  
`"bt_set_challenge <number> <number>"`.  
`"btsc <number> <number> "`.  
***
`"beasts_tower_reset <param>: beasts_tower_reset"`.  
`"beasts_tower_reset <number>"`.  
`"btr <number>"`.  
***
`"/reload_high_lottery_db : reload high lottery db"`.  
`"reload_high_lottery_db"`.  
`"rhld"`.  
***
`"/set_statue2 <player_id> <node> <id> <action> <key>: set statue2"`.  
`"set_statue2 <number> <number> <number> <number> <number>"`.  
`"sst2 <number> <number> <number> <number> <number>"`.  
***
`"/super_clear_bag_item: super_clear_bag_item"`.  
`"scbi"`.  
***
`"/strenghten_equipments <number>"`.  
`"strenghten_equipments <number>"`.  
***
`"/change_gender <gender_id> : change character gender"`.  
`"change_gender <number>"`.  
`"cg <number>"`.  
***
`"/accept_mission <mission_id>"`.  
`"accept_mission <number>"`.  
`"am <number>"`.  
***
`"/clear_all_collection: clear_all_collection"`.  
`"cac"`.  
***
`"/lottery_dice_test <times> <mode> <category> <level>"`.  
`"lottery_dice_test <number> <number> <number> <number>"`.  
`"ldt <number> <number> <number> <number>"`.  
***
`"/send_treasure <mode> <award_id>"`.  
`"send_treasure <number> <number>"`.  
`"sdtr <number> <number>"`.  
***
`"/close <word> <number> <number> <number>"`.  
`"close <word> <number> <number> <number>"`.  
`"clo <word> <number> <number> <number>"`.  
***
`"/strengthen_equipments_2 <number> <number> <number> <number>"`.  
`"strengthen_equipments_2 <number> <number> <number> <number>"`.  
`"se2 <number> <number> <number> <number>"`.  
***
`"/beasts_tower_next <number>"`.  
`"btn <number>"`.  
***
`"/set_lover_challenge <number> <number> <number>"`.  
`"set_lover_challenge <number> <number> <number>"`.  
`"slc <number> <number> <number>"`.  
***
`"/set_first_create_time <number> <number> <number>"`.  
`"set_first_create_time <number> <number> <number>"`.  
`"sfct <number> <number> <number>"`.  
***
`"/rainbow_reset <number>"`.  
`"rreset <number>"`.  
***
`"/rainbow_roll <number>"`.  
`"rroll <number>"`.  
***
`"/rainbow_num <number>"`.  
`"rnum <number>"`.  
***
`"/reset_itemmall_new_account_amount_limit <account_id>: reset itemmall new_account amount limit"`.  
`"reset_itemmall_new_account_amount_limit <number>"`.  
`"rinaal <number>"`.  
***
`"/rainbow_gain_count <number> <number>: rainbow_gain_count"`.  
`"rainbow_gain_count <number> <number>"`.  
`"rgc <number> <number>"`.  
***
`"/clone_crystal_combo <number> <number> <number> <number>: clone_crystal_combo"`.  
`"clone_crystal_combo <number> <number> <number> <number>"`.  
`"ccc <number> <number> <number> <number>"`.  
***
`"/set_family_wishing_well <number> <number> <number> <number>: set_family_wishing_well"`.  
`"set_family_wishing_well <number> <number> <number> <number>"`.  
`"sfww <number> <number> <number> <number>"`.  
***
`"/clone_souvenir_combo <number> <number> <number> <number>: clone_souvenir_combo"`.  
`"clone_souvenir_combo <number> <number> <number> <number>"`.  
`"csc <number> <number> <number> <number>"`.  
***
`"/cross_zone_server <number> <number> : cross_zone_server"`.  
`"cross_zone_server <number> <number>"`.  
`"czs <number> <number>"`.  
***
`"/reset_itemmall_new_account_amount_limit_all : reset itemmall new_account amount limit all"`.  
`"reset_itemmall_new_account_amount_limit_all"`.  
`"rinaala"`.  
***
`"/set_first_create_time_all <number> <number>"`.  
`"set_first_create_time_all <number> <number>"`.  
`"sfcta <number> <number>"`.  
***
`"/close_tablet <number>"`.  
`"ctab <number>"`.  
***
`"/set_tablet_level <number>"`.  
`"stabl <number>"`.  
***
`"/gain_tablet_exp <number>"`.  
`"gtabe <number>"`.  
***
`"/get_all_tablet_skill <number>"`.  
`"gatabs <number>"`.  
***
`"/get_tablet_skill <number> <number>"`.  
`"get_tablet_skill <number> <number>"`.  
`"gtabs <number> <number>"`.  
***
`"/autoclick_punish_open <open>: autoclick_punish_open"`.  
`"autoclick_punish_open <number>"`.  
`"apo <number>"`.  

