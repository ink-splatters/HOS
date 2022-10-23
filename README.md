# Hack ØS

macOS ruthless System Volume dissection wielding rusty pathologist' tools which Dexter would endorse

(primarily `rm -rf ` and  `/usr/libexec/PlistBuddy`)

## Objectives

### Tactical

- domination (in addition to disabled SIP, disarming AMFI in order to abuse the juicy private entitlements)
- liposuction ( useless apps, kexts, `AWD` and other bloat as telemetry/diagnostics tools are to be removed )
- lobotomy ( all the Siri smartness:  `assistantd`, `triald`, `parsec`, `reversetemplated`, `routined`, `destinationd`, etc.) is doomed,
	 along with disrooting the related frameworks ( leaving alone the frameworks migrated to dlyd cache, for now)
- induced amnesia (tampering with FeatureFlags, primarily to disable "disclosure" flags, as well as removing corresponding daemons and agents, in hope to effectively disrupt the patient's calling-home abilities 

### Strategic

- custom XNU build to lift the remains of the protections, enabling what is disabled, e.g. bind mounts 
- `nix`, `yabai`, `nvim` OOB integration
- ditching Apple LLVM stubs / ending the cravings for Xcode
...




