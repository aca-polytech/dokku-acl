#!/usr/bin/env bash

set -eo pipefail; [[ $DOKKU_TRACE ]] && set -x
source "$PLUGIN_CORE_AVAILABLE_PATH/common/functions"


APP="$1";
ACL_PATH="$DOKKU_ROOT/$APP/acl"

ACL_FILE="$ACL_PATH/$NAME"
mkdir "$ACL_PATH"
touch "$ACL_FILE"

dokku_log_info1 "Add ACL for $NAME"
