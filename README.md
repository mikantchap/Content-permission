# Content permission
Custom module to control access to certain nodes

## Pevents access to certain nodes for users with LOCAL HW REPORTS EDITOR role 

If a user with LOCAL HW REPORTS EDITOR role attempts to edit a RL whose LHW values do not coincide with the user’s LHW values, then they should be denied access.

The field 'field_local_healthwatch' is used in Reports Library content type. The eqivalent field in users' accounts is field 'field_local_healthwatch'.
