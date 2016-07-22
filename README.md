# APAnti
Garry's Mod (GMod) Anti Prop Griefing Solution. (Test Build!)

Remember that this is the TEST build, expect things to break. **Be ready to report any issues.**<br/>
Update Notes: https://github.com/LuaTenshi/APAnti/commit/ceffc4e78f2f8e2f03e078a816d80433359a2164


Note: This version is currently untested if you are unsure about using it or are afraid to break things please use https://github.com/LuaTenshi/GLua/tree/master/APAnti

GitHub: Guess.<br/>
Pronunciation: Ae Pea Anti<br/>
Note: This now comes with a tool for unghosting props without having to physgun them. Useful when building.<br/>
Note: What is it with you guys being so lewd and calling this "a panty".<br/>

# Features & Commands
    Command = Default Value : Description
    
    --- Base AntiPK ---
    AntiPK                   = 1 : Setting this to 1 will enable Anti Prop Kill.
    Debug                    = 0 : Setting this to 1 will enable Debug Output. Setting this to 2 will log the output. (Warning: This command is spammy!)
    PhysgunNerf              = 1 : Setting this to 1 will limit the physgun speed.
    BlockVehicleDamage       = 1 : Setting this to 1 will stop vehicle damage.
    BlockExplosionDamage     = 1 : Setting this to 1 will block explosion damage.
    BlockWorldDamage         = 0 : Setting this to 1 will block world damage.
    BlockPropDamage          = 0 : Setting this to 1 will always block "prop_" damage.
    KillOwnership            = 0 : Setting this to 1 will reward kills for "prop_" damage based on the props owner. (Warning: Due to possible entropy this may not be accurate!)
    Method                   = 0 : Setting this to 1 will use the Blacklist, setting it to 0 will predict.
    PropsOnly                = 0 : Setting this to 1 will effect only "prop_" classes.
    BadTime                  = 0.15 : How long (in seconds) does an entity have to wait to become "good" and be able to do damage again. (Minimum is 0.15)
    --- Prop Control ---
    UnbreakableProps         = 0 : Setting this to 1 will make props unbreakable.
    NoCollideVehicles        = 1 : Setting this to 1 will make vehicles not collide with players.
    AnnoySurf                = 1 : Setting this to 1 will make prop surf annoying.
    NoThrow                  = 0 : Setting this to 1 will stop people from throwing props.
    MaxMass                  = 1500 : This is the max weight a /spawned/ object may have. Minimum is 1, 0 Disables.
    --- Freezing ---
    StopMassUnfreeze         = 1 : Setting this to 1 will stop people from unfreezing all their props by double tapping R.
    StopRUnfreeze            = 0 : Setting this to 1 will stop people from unfreezing props by tapping R.
    FreezeOnHit              = 1 : Setting this to 1 will freeze props when they hit a player. (Needs AntiPK.)
    FreezeOnDrop             = 0 : Setting this to 1 will freezes props when a player lets go of them.
    FreezeOnUnghost          = 1 : Setting this to 1 will freeze props when they unghost.
    FreezePassive            = 0 : Setting this to 1 will freeze props passivly.
    --- Ghosting ---
    AntiPush                 = 0 : Setting this to 1 will enable Anti Prop Push (Ghosting).
    GhostSpawn               = 0 : Setting this to 1 will enable ghosting on spawn.
    GhostFreeze              = 0 : Setting this to 1 will freeze ghosts.
    UnGhostPassive           = 0 : Setting this to 1 will passivly unghost props. (Needs AntiPush.)
    GhostsNoCollide          = 0 : Setting this to 1 will make ghosts nocollide with everything.

**You can toggle all of the above features to make this Anti Prop Kill work exactly how you want it to.**
