target_sources(client PRIVATE
	ammo.cpp
	ammo.h
	ammohistory.cpp
	ammohistory.h
	ammo_secondary.cpp
	battery.cpp
	bench.h
	camera.h
	cdll_int.cpp
	cl_dll.h
	cl_util.h
	com_weapons.cpp
	com_weapons.h
	death.cpp
	demo.cpp
	demo.h
	entity.cpp
	events.cpp
	eventscripts.h
	ev_common.cpp
	ev_hldm.cpp
	ev_hldm.h
	Exports.h
	flashlight.cpp
	GameStudioModelRenderer.cpp
	GameStudioModelRenderer.h
	geiger.cpp
	global_consts.h
	health.cpp
	health.h
	hud.cpp
	hud.h
	hud_bench.cpp
	hud_benchtrace.cpp
	hud_benchtrace.h
	hud_msg.cpp
	hud_redraw.cpp
	hud_spectator.cpp
	hud_spectator.h
	hud_update.cpp
	input.cpp
	inputw32.cpp
	interpolation.cpp
	interpolation.h
	in_camera.cpp
	in_defs.h
	kbutton.h
	menu.cpp
	message.cpp
	player_info.h
	saytext.cpp
	statusbar.cpp
	status_icons.cpp
	StudioModelRenderer.cpp
	StudioModelRenderer.h
	studio_util.cpp
	studio_util.h
	text_message.cpp
	tf_defs.h
	train.cpp
	tri.cpp
	tri.h
	util.cpp
	vgui_ClassMenu.cpp
	vgui_CustomObjects.cpp
	vgui_int.cpp
	vgui_int.h
	vgui_MOTDWindow.cpp
	vgui_SchemeManager.cpp
	vgui_SchemeManager.h
	vgui_ScorePanel.cpp
	vgui_ScorePanel.h
	vgui_SpectatorPanel.cpp
	vgui_SpectatorPanel.h
	vgui_TeamFortressViewport.cpp
	vgui_TeamFortressViewport.h
	vgui_teammenu.cpp
	view.cpp
	view.h
	voice_status.cpp
	voice_status.h
	wrect.h
	hl/hl_baseentity.cpp
	hl/hl_events.cpp
	hl/hl_objects.cpp
	hl/hl_weapons.cpp
	../dlls/crossbow.cpp
	../dlls/crowbar.cpp
	../dlls/egon.cpp
	../dlls/gauss.cpp
	../dlls/handgrenade.cpp
	../dlls/hornetgun.cpp
	../dlls/mp5.cpp
	../dlls/python.cpp
	../dlls/rpg.cpp
	../dlls/satchel.cpp
	../dlls/shotgun.cpp
	../dlls/squeakgrenade.cpp
	../dlls/tripmine.cpp
	../dlls/weapons_shared.cpp
	../dlls/wpn_shared/hl_wpn_glock.cpp
	../common/beamdef.h
	../common/cl_entity.h
	../common/com_model.h
	../common/const.h
	../common/con_nprint.h
	../common/crc.h
	../common/cvardef.h
	../common/demo_api.h
	../common/director_cmds.h
	../common/dlight.h
	../common/dll_state.h
	../common/entity_state.h
	../common/entity_types.h
	../common/enums.h
	../common/event_api.h
	../common/event_args.h
	../common/event_flags.h
	../common/hltv.h
	# ../common/interface.cpp # Do not include, version from /public is used
	../common/interface.h
	../common/in_buttons.h
	../common/ivoicetweak.h
	../common/mathlib.cpp
	../common/mathlib.h
	../common/netadr.h
	../common/net_api.h
	../common/nowin.h
	../common/parsemsg.cpp
	../common/parsemsg.h
	../common/particledef.h
	../common/Platform.h
	../common/pmtrace.h
	../common/port.h
	../common/qfont.h
	../common/ref_params.h
	../common/r_efx.h
	../common/r_studioint.h
	../common/screenfade.h
	../common/Sequence.h
	../common/studio_event.h
	../common/triangleapi.h
	../common/usercmd.h
	../common/weaponinfo.h
	../common/winsani_in.h
	../common/winsani_out.h
	../game_shared/bitvec.h
	../game_shared/vgui_checkbutton2.cpp
	../game_shared/vgui_checkbutton2.h
	../game_shared/vgui_defaultinputsignal.h
	../game_shared/vgui_grid.cpp
	../game_shared/vgui_grid.h
	../game_shared/vgui_helpers.cpp
	../game_shared/vgui_helpers.h
	../game_shared/vgui_listbox.cpp
	../game_shared/vgui_listbox.h
	../game_shared/vgui_loadtga.cpp
	../game_shared/vgui_loadtga.h
	../game_shared/vgui_scrollbar2.cpp
	../game_shared/vgui_scrollbar2.h
	../game_shared/vgui_slider2.cpp
	../game_shared/vgui_slider2.h
	../game_shared/voice_banmgr.cpp
	../game_shared/voice_banmgr.h
	../game_shared/voice_common.h
	../pm_shared/pm_debug.cpp
	../pm_shared/pm_debug.h
	../pm_shared/pm_defs.h
	../pm_shared/pm_info.h
	../pm_shared/pm_materials.h
	../pm_shared/pm_math.cpp
	../pm_shared/pm_movevars.h
	../pm_shared/pm_shared.cpp
	../pm_shared/pm_shared.h
	../public/archtypes.h
	../public/FileSystem.h
	../public/interface.cpp
	../public/interface.h
	../public/keydefs.h
	../public/particleman.h
	../public/pman_particlemem.h
	../public/pman_triangleffect.h
	../public/cl_dll/IGameClientExports.h
	../public/steam/steamtypes.h
)
