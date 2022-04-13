# -OnInputEnterKeyOne-
CtrlSetOnEvent(-1, "OnInputEnterKeyOne")     GUICtrlCreateInput("This text 2", 5, 35, 200, 21, BitOR($GUI_SS_DEFAULT_INPUT, $ES_WANTRETURN))     GUICtrlSetOnEvent(-1, "OnInputEnterKeyTwo")
