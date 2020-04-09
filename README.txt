/*************************************************************************
   map-utcsud_13_v1.1_src.zip
   Map source package for software 'Tremulous/ Quake3' (www.tremulous.net)
   Copyright (c) yalt / Matth. All rights reserved.
   Licensed under the MIT License (see: /LICENSE.txt). 
************************************************************************/

INSTALL: (HDD):/%PATH%/Tremulous/base/*
LEVELNAME: U.T.C.S UD / UTCS - Ultra Definition
ADDITIVE: UTCSUD for Tremulous-Modification 'Tremulous 1.3'
MAINFILE: utcsud_13.map
AUTHOR: yalt/ Matth
DATE: 15.10.2016
SDK: netradiant-20150621
COMPILER: Q3MAP2, 2.5.17n-git-1451c06
 |-SETTINGS: 
    -meta -custinfoparms -samplesize 4 -deepbsp; 
    -vis -saveprt -hint; 
    -light -shade -dirty -dark -patchshadows -samples 3 -cpma -deluxe

--------------------------------------------------------------------------------
DEVIATING-AUTHORS / ADDONS:
1.
'evillair's Quake4 eX Texture Set / eX'
Author: Yves Allaire aka "evillair", admin@evillair.net, www.evillair.net

2.
'SkyBox'
Author: Stijn "Ingar" Buys <ingar@osirion.org>

3.
'Granger advertising material'
Author: GrangerHub-Project/ Tremulous 1.3, www.grangerhub.com

(All materials have been modified by Matth/ yalt)

--------------------------------------------------------------------------------
Filelist:
X
|   LICENSE.txt
|   README.txt
|   
+---env
|   \---utcsud
|           ud_bk.jpg
|           ud_dn.jpg
|           ud_ft.jpg
|           ud_lf.jpg
|           ud_rt.jpg
|           ud_up.jpg
|           
+---levelshots
|       utcsud.jpg
|       
+---maps
|       utcsud_13.map
|       
+---models
|   \---barrel
|           barrel_red_radio.jpg
|           barrel_red_radio.MD3
|           
+---scripts
|       common-trem.shader
|       common.shader
|       eX.mtr
|       eX.shader
|       shaderlist.txt
|       utcsud.arena
|       utcsud.mtr
|       utcsud.shader
|       
+---sound
|   +---movers
|   |   \---plats
|   |           pt1_end.wav
|   |           pt1_strt.wav
|   |           
|   \---utcsud
|           fan.wav
|           in_loop.wav
|           pump.wav
|           sound_gas.wav
|           
+---textures
|   +---common
|   |       areaportal.tga
|   |       black.tga
|   |       botclip.tga
|   |       caulk.tga
|   |       clip.tga
|   |       clusterportal.tga
|   |       cushion.tga
|   |       donotenter.tga
|   |       full_clip.tga
|   |       hint.tga
|   |       hintskip.tga
|   |       invisible.tga
|   |       ladder.tga
|   |       lightgrid.tga
|   |       metalclip.tga
|   |       missileclip.tga
|   |       nodraw.tga
|   |       nodrawnonsolid.tga
|   |       nodrop.tga
|   |       noimpact.tga
|   |       nolightmap.tga
|   |       origin.tga
|   |       qer_invisible.tga
|   |       qer_mirror.tga
|   |       qer_noimpact.tga
|   |       qer_nolightmap.tga
|   |       qer_portal.tga
|   |       slick.tga
|   |       terrain.tga
|   |       trigger.tga
|   |       weapclip.tga
|   |       white.tga
|   |       
|   +---eX
|   |   |   eXmetalBase01_d.tga
|   |   |   eXmetalBase02_d.tga
|   |   |   eXmetalBase03_d.tga
|   |   |   eXmetalBase04_d.tga
|   |   |   eXmetalBase05Rust_d.tga
|   |   |   eXmetalBase06rust_d.tga
|   |   |   eXmetalBase07rust_d.tga
|   |   |   eXmetalFloor02_d.tga
|   |   |   eXmetalrib01_d.tga
|   |   |   eXmetal_plate01B_d.tga
|   |   |   eXmetal_plate01c_d.tga
|   |   |   eXmetal_plate01_d.tga
|   |   |   eX_clangfloor_01b_d.tga
|   |   |   eX_clangfloor_01_d.tga
|   |   |   eX_cretebase_01_d.tga
|   |   |   eX_cretebase_02_d.tga
|   |   |   eX_cretebase_03_dark_d.tga
|   |   |   eX_cretefloor_01b_d.tga
|   |   |   eX_cretefloor_01_d.tga
|   |   |   eX_cretewall_01_d.tga
|   |   |   eX_cretewall_02_d.tga
|   |   |   eX_cretewall_03b_d.tga
|   |   |   eX_cretewall_03_d.tga
|   |   |   eX_deswall_01_d.tga
|   |   |   eX_floorpanel_01_d.tga
|   |   |   eX_floor_grate03_d.tga
|   |   |   eX_floor_grate_03_128_d.tga
|   |   |   eX_floor_grate_03_d.tga
|   |   |   eX_floor_mtl_grate_01_d.tga
|   |   |   eX_floor_mtl_wrn_01_d.tga
|   |   |   eX_floor_simple_05_d.tga
|   |   |   eX_floor_simplines_d.tga
|   |   |   eX_floor_tile_03_d.tga
|   |   |   eX_floor_tread_01_d.tga
|   |   |   eX_lightpanel_01_add.tga
|   |   |   eX_lightpanel_01_d.tga
|   |   |   eX_light_u201_add.tga
|   |   |   eX_light_u201_d.tga
|   |   |   eX_metalplate_01_d.tga
|   |   |   eX_metalSupp01_d.tga
|   |   |   eX_metalwall02_d.tga
|   |   |   eX_mtl_bigplate_04b_d.tga
|   |   |   eX_mtl_bigplate_04_d.tga
|   |   |   eX_mtl_panel_02_d.tga
|   |   |   eX_mtl_panel_03_d.tga
|   |   |   eX_mtl_panel_04_d.tga
|   |   |   eX_q2_01b_d.tga
|   |   |   eX_q2_01c_d.tga
|   |   |   eX_q2_01d_d.tga
|   |   |   eX_q2_01e_d.tga
|   |   |   eX_q2_01_d.tga
|   |   |   eX_rndfloor_01_d.tga
|   |   |   eX_rndfloor_02_d.tga
|   |   |   eX_rplates_01_d.tga
|   |   |   eX_steptop_01_d.tga
|   |   |   eX_trim_01_d.tga
|   |   |   eX_trim_baseboard_02_d.tga
|   |   |   eX_trim_baseboard_03_d.tga
|   |   |   eX_trim_baseboard_d.tga
|   |   |   eX_trim_psimple_04_d.tga
|   |   |   eX_trim_psimple_05_d.tga
|   |   |   eX_trim_simple03_d.tga
|   |   |   eX_trim_simple_01_d.tga
|   |   |   eX_trim_support_03_d.tga
|   |   |   eX_trim_vert_01_d.tga
|   |   |   eX_wall_01b_d.tga
|   |   |   eX_wall_01_d.tga
|   |   |   eX_wall_b01_d.tga
|   |   |   eX_wall_bigrib_02_d.tga
|   |   |   eX_wall_bplate_06_d.tga
|   |   |   eX_wall_panels_08b_d.tga
|   |   |   eX_wall_panels_08_d.tga
|   |   |   eX_wall_panel_05_d.tga
|   |   |   eX_wall_pipe_d.tga
|   |   |   eX_wall_u207_d.tga
|   |   |   
|   |   \---gl2
|   |           eXmetalBase01_local.tga
|   |           eXmetalBase01_s.tga
|   |           eXmetalBase02_local.tga
|   |           eXmetalBase02_s.tga
|   |           eXmetalBase03_local.tga
|   |           eXmetalBase03_s.tga
|   |           eXmetalBase05Rust_local.tga
|   |           eXmetalBase05Rust_s.tga
|   |           eXmetalFloor02_local.tga
|   |           eXmetalFloor02_s.tga
|   |           eXmetalrib01_local.tga
|   |           eXmetalrib01_s.tga
|   |           eXmetal_plate01B_local.tga
|   |           eXmetal_plate01B_s.tga
|   |           eXmetal_plate01c_local.tga
|   |           eXmetal_plate01c_s.tga
|   |           eXmetal_plate01_local.tga
|   |           eXmetal_plate01_s.tga
|   |           eX_clangfloor_01_local.tga
|   |           eX_clangfloor_01_s.tga
|   |           eX_cretebase_01_local.tga
|   |           eX_cretebase_01_s.tga
|   |           eX_cretefloor_01b_local.tga
|   |           eX_cretefloor_01b_s.tga
|   |           eX_cretefloor_01_local.tga
|   |           eX_cretefloor_01_s.tga
|   |           eX_cretewall_01_local.tga
|   |           eX_cretewall_01_s.tga
|   |           eX_cretewall_02_local.tga
|   |           eX_cretewall_02_s.tga
|   |           eX_cretewall_03b_local.tga
|   |           eX_cretewall_03b_s.tga
|   |           eX_cretewall_03_local.tga
|   |           eX_cretewall_03_s.tga
|   |           eX_deswall_01_local.tga
|   |           eX_deswall_01_s.tga
|   |           eX_floorpanel_01_local.tga
|   |           eX_floorpanel_01_s.tga
|   |           eX_floor_grate03_local.tga
|   |           eX_floor_grate03_s.tga
|   |           eX_floor_grate_03_128_local.tga
|   |           eX_floor_grate_03_128_s.tga
|   |           eX_floor_grate_03_local.tga
|   |           eX_floor_grate_03_s.tga
|   |           eX_floor_mtl_grate_01_local.tga
|   |           eX_floor_mtl_grate_01_s.tga
|   |           eX_floor_mtl_wrn_01_local.tga
|   |           eX_floor_mtl_wrn_01_s.tga
|   |           eX_floor_simple_05_local.tga
|   |           eX_floor_simple_05_s.tga
|   |           eX_floor_simplines_local.tga
|   |           eX_floor_simplines_s.tga
|   |           eX_floor_tile_03_local.tga
|   |           eX_floor_tile_03_s.tga
|   |           eX_floor_tread_01_local.tga
|   |           eX_floor_tread_01_s.tga
|   |           eX_lightpanel_01_local.tga
|   |           eX_lightpanel_01_s.tga
|   |           eX_light_u201_local.tga
|   |           eX_light_u201_s.tga
|   |           eX_metalplate_01_local.tga
|   |           eX_metalplate_01_s.tga
|   |           eX_metalSupp01_local.tga
|   |           eX_metalSupp01_s.tga
|   |           eX_metalwall02_local.tga
|   |           eX_metalwall02_s.tga
|   |           eX_mtl_bigplate_04b_local.tga
|   |           eX_mtl_bigplate_04b_s.tga
|   |           eX_mtl_bigplate_04_local.tga
|   |           eX_mtl_bigplate_04_s.tga
|   |           eX_mtl_panel_02_local.tga
|   |           eX_mtl_panel_02_s.tga
|   |           eX_mtl_panel_03_local.tga
|   |           eX_mtl_panel_03_s.tga
|   |           eX_mtl_panel_04_local.tga
|   |           eX_mtl_panel_04_s.tga
|   |           eX_q2_01b_local.tga
|   |           eX_q2_01b_s.tga
|   |           eX_q2_01c_local.tga
|   |           eX_q2_01c_s.tga
|   |           eX_q2_01d_local.tga
|   |           eX_q2_01d_s.tga
|   |           eX_q2_01e_local.tga
|   |           eX_q2_01e_s.tga
|   |           eX_q2_01_local.tga
|   |           eX_q2_01_s.tga
|   |           eX_rndfloor_01_local.tga
|   |           eX_rndfloor_01_s.tga
|   |           eX_rndfloor_02_local.tga
|   |           eX_rndfloor_02_s.tga
|   |           eX_rplates_01_local.tga
|   |           eX_rplates_01_s.tga
|   |           eX_steptop_01_local.tga
|   |           eX_steptop_01_s.tga
|   |           eX_trim_01_local.tga
|   |           eX_trim_01_s.tga
|   |           eX_trim_baseboard_02_local.tga
|   |           eX_trim_baseboard_02_s.tga
|   |           eX_trim_baseboard_03_local.tga
|   |           eX_trim_baseboard_03_s.tga
|   |           eX_trim_baseboard_local.tga
|   |           eX_trim_baseboard_s.tga
|   |           eX_trim_psimple_04_local.tga
|   |           eX_trim_psimple_04_s.tga
|   |           eX_trim_psimple_05_local.tga
|   |           eX_trim_psimple_05_s.tga
|   |           eX_trim_simple03_local.tga
|   |           eX_trim_simple03_s.tga
|   |           eX_trim_simple_01_local.tga
|   |           eX_trim_simple_01_s.tga
|   |           eX_trim_support_03_local.tga
|   |           eX_trim_support_03_s.tga
|   |           eX_trim_vert_01_local.tga
|   |           eX_trim_vert_01_s.tga
|   |           eX_wall_01_local.tga
|   |           eX_wall_01_s.tga
|   |           eX_wall_b01_local.tga
|   |           eX_wall_b01_s.tga
|   |           eX_wall_bigrib_02_local.tga
|   |           eX_wall_bigrib_02_s.tga
|   |           eX_wall_bplate_06_local.tga
|   |           eX_wall_bplate_06_s.tga
|   |           eX_wall_panels_08b_local.tga
|   |           eX_wall_panels_08b_s.tga
|   |           eX_wall_panels_08_local.tga
|   |           eX_wall_panels_08_s.tga
|   |           eX_wall_panel_05_local.tga
|   |           eX_wall_panel_05_s.tga
|   |           eX_wall_pipe_local.tga
|   |           eX_wall_pipe_s.tga
|   |           eX_wall_u207_local.tga
|   |           eX_wall_u207_s.tga
|   |           
|   +---radiant
|   |       notex.tga
|   |       shadernotex.tga
|   |       
|   \---utcsud
|           blk.jpg
|           credits.jpg
|           credits_add.jpg
|           credits_lines.jpg
|           trem1_3_ad.jpg
|           utcsud_03.jpg
|           utcsud_03b.jpg
|           utcsud_03r.jpg
|           utcsud_03_blend.jpg
|           utcsud_03_blend_blue.jpg
|           utcsud_03_blend_red.jpg
|           utcsud_03_n.jpg
|           utcsud_03_s.jpg
|           vent_01.tga
|           
\---_PSD
        levelshot.psd
        