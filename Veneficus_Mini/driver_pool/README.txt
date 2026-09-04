# +--------------------------------------------------------------------------+
# |          _   ___ ___    _   __  __   _   ___   _      _   ___ ___        |
# |         /_\ | _ ) _ \  /_\  \ \/ /  /_\ / __| | |    /_\ | _ ) __|       |
# |        / _ \| _ \   / / _ \  >  <  / _ \\__ \ | |__ / _ \| _ \__ \       |
# |       /_/ \_\___/_|_\/_/ \_\/_/\_\/_/ \_\___/ |____/_/ \_\___/___/       |
# |                                                                          |
# |                     analyze  /  reverse  /  disclose                     |
# |                                                                          |
# |                       Veneficus Mini Worm Toolkit                        |
# |           https://github.com/abraxas/veneficus-implant-public            |
# |                                                                          |
# |   I did not write this kit or code. Credit: @YogSoth0. Analyzed as-is.   |
# |                                                                          |
# | abraxaslabs.tech                                           @abraxas_null |
# +--------------------------------------------------------------------------+

driver_pool/
    Empty in this outline.

    At run time the agent expects signed-but-vulnerable kernel images
    here, one file per pool slot (see src/driver_assist.pseudo).

    This public packet does not ship, name, or hash those files.
