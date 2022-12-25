
# heroku-buildpack-shellinabox

## Requirements
  * [Apt buildpack](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-apt) to run after this buildpack

## Environment variables
  * SHELLINABOX_SERVICE_COMMAND (optional) - specifies which shell/process to enter after login check. By default bash.

The following will only work if SHELLINABOX_WRAPPER_SCRIPT_NAME is unchanged:
  * SHELLINABOX_WRAPPER_SCRIPT_NAME (optional) - a manual script that starts shellinabox daemon and give shell access
  * SHELLINABOX_PORT (optional) - a port on which shellinabox run on. By default run on heroku's specified port.
  * SHELLINABOX_OPTS (optional) - additional options for shellinabox.
