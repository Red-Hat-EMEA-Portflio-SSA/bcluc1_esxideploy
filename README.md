# Workflow of Usecase 1
# runs on cmd line like this:
# . ../bcl_setup/bcl_setup_config/env.sh 
# ansible-navigator run workflow.yml -e @bcluc1_esxideploy_config/extra_vars.yml -e @bcluc1_esxideploy_config/vaulted_vars.yml -e debug=true -e remove=true --eei localhost/bcl-ov--eei localhost/bcl-ov:22  --pp never
