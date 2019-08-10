#
# Copyright (C) 2016+     AzerothCore <www.azerothcore.org>, released under GNU AGPL3 v3 license: https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-AGPL3
#

# Add script files
AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/npc_arena1v1.cpp")

# Add scripts to script loader
AC_ADD_SCRIPT_LOADER("1v1Arena" "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

# Add config file
AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/1v1arena.conf.dist")
