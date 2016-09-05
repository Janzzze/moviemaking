

## BINDS
| Key  | Function                               |
|------|----------------------------------------|
| F3   | demo_pause                             |
| F4   | demo_resume                            |
| F5   | endmovie; mirv_streams record end      |
| F6   | toggle cl_draw_only_deathnotices 1 / 0 |
| del  | mirv_campath enable 0                  |
| end  | mirv_campath load campath              |
| home | mirv_campath save campath              |
| ins  | mirv_campath enable 1                  |
| pgdn | mirv_campath clear                     |
| pgup | mirv_campath add                       |


## ALIAS

| Key           | Function                                          |
|---------------|---------------------------------------------------|
| hud           | toggle hud on / off                               |
| skins         | toggle skins on / off                             |
| flash         | toggle flash on / off                             |
| smoke         | toggle smoke on / off                             |
| assists       | toggle assists on /off                            |
| clantag       | toggle clantag on /off                            |
| skybox        | show a list of skyboxes                           |
| deathmsgclear | clear mirv_deathmsg, mirv_replace_name            |
| deathmsgdebug | toggle mirv_deathmsg, mirv_replace_name debugging |
| 'qq' & 'qqq'  | quit                                              |
| 'dc' & 'dd'   | disconnect                                        |

## MIRV_DEATHMSG CheatSheet
	mirv_deathmsg block !uid *
	mirv_deathmsg cfg noticelifetime f
	mirv_deathmsg highlightId uid
	mirv_replace_name n "New Name" 

## mirv_streams actions stock action

* black
* debugDepth
* debugDump (don't use)
* draw
* drawDepth
* mask
* noDraw
* white

## mirv_streams stream types

* normal - normal stream
* baseFx - allows effects, no different unless edited
* depth - depth stream. WILL NOT WORK PROPERLY ATM!
* matteWorld - matte world stream.
* depthWorld - Add a depth world stream. WILL NOT WORK PROPERLY ATM!
* matteEntity - matte entity stream.
* depthEntity - depth entity stream. WILL NOT WORK PROPERLY ATM!
* developer - developer stream.
* alphaMatteEntity - entity stream with alpha matte combined into a single stream.
* alphaWorld - alpha world stream.
* alphaMatte - alpha matte stream (alpha channel of alphaMatteEntity).
* alphaEntity - alpha entity stream (color channel of alphaMatteEntity).

## mirv_streams actionFilter CheatSheet

### Nametags

	"models/weapons/uid/\*"
	"models/weapons/uid_weaponpreview/\*"

### Weapon Viewmodels

	"models/weapons/v_models/\*"

### Weapon Worldmodels

	"models/weapons/w_models/\*"

### Weapon Skins

	"cs_custom_material_\*"

### Cleanup WeaponScopes

	"dev/scope_vignette"
	"dev/vignette"
	"sprites/scope_line_blur"
	"models/weapons/shared/scope/scope_lens_dirt"
	"overlays/scope_lens"

### Scoped Weapons Viewmodel Lens For AlphaMatte 

	"models/weapons/shared/scope/\*"		

### Remove Chickens, Birthdays and Holidays

	"models/player/holiday/\*"
	"models/props/holiday_light/\*"
	"models/props/props_crossover/\*"
	"models/props_critters/\*"
	"models/props/props_critters/\*"
	"models/props_farm/\*"
	"particle/feathers/\*"
	"particle/confetti/\*"

### some retarded hud things

	"hud/\*"
	"vgui/\*"

### maybe usefull dunno

	"models/weapons/customization/\*"































