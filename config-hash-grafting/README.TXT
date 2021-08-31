
SUMMARY:

Load all default vars as separate hashes
Graft each default var hash onto pg_config hash
Overwrite default values with custom values in pg_config
Overwritten values only allowed with 'defined' default vars

What you are left with is a single hash that includes all key/vals 
that began in defaults and were updated with custom values

